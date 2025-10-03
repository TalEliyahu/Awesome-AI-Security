### Vulnerability & Threat Intelligence (Live Feeds → Unified Dataset Spec) <a name="vulnerability--threat-intelligence-live-feeds--unified-dataset-spec"></a>

> These are **live sources** (not static dumps). Use the schema below to build a **single, de-duplicated dataset** (CSV/Parquet/JSONL) consumable for AI security research, curation, and dashboards.

### Normalized schema (recommended)
| Field | Type | Description |
|---|---|---|
| `source` | string | Feed/system name, e.g., `MITRE_CVE`, `NVD`, `GHSA`, `ZDI`, `KEV`, `CWE`, `CAPEC`, `MITRE_ATTACK`, `D3FEND`, `AttackerKB`, `ExploitDB`, `Bugtraq`, `FullDisclosure`, `oss-security`, `Linux-CVE-Announce`, `GitHub`, `git.kernel.org` |
| `source_id` | string | Primary ID within the source (e.g., CVE-ID, GHSA-ID, ZDI-ID, message URL, commit hash) |
| `title` | string | Title/subject of the record |
| `description` | string | Short summary (markdown or plain) |
| `published_at` | datetime | First published timestamp from the source |
| `modified_at` | datetime | Last updated timestamp (if present) |
| `cve_ids` | array\<string> | Referenced CVE(s) (0..n) |
| `cwe_ids` | array\<string> | Referenced CWE(s) (0..n) |
| `cvss_base` | float | CVSS base score (v3.x preferred) |
| `cvss_vector` | string | CVSS vector (e.g., `CVSS:3.1/...`) |
| `severity` | enum | `CRITICAL|HIGH|MEDIUM|LOW|UNKNOWN` (normalize per-source) |
| `affected_products` | array\<string> | Prefer CPE names (`cpe:2.3:...`) or purls (`pkg:`) |
| `exploited_in_the_wild` | boolean | True if listed in KEV or stated by source |
| `exploit_refs` | array\<string> | Links to PoCs/exploits (e.g., Exploit-DB, gists) |
| `patch_refs` | array\<string> | Links to commits/releases/vendor advisories |
| `references` | array\<string> | All other references/URLs cited by the record |
| `tags` | array\<string> | Freeform labels (e.g., `deserialization`, `RCE`, `kernel`) |
| `license` | string | Source license/terms if available |
| `retrieved_at` | datetime | Your crawler fetch time |

### Dataset categories
- **CVE Record** — CVE entries aggregated from multiple databases (e.g., MITRE, NVD, ZDI, GitHub).
- **Assessment** — signals/metadata tied to CVEs (e.g., CPE, CVSS, KEV, AttackerKB) and taxonomies (CWE, CAPEC, ATT&CK, D3FEND).
- **PoC** — exploits or proof-of-concepts (runnable code or steps to reproduce).
- **Mail** — messages related to one or more CVEs (mailing list posts/threads).
- **Patch** — code diffs from commits, with optional commit messages.

### Core CVE databases & catalogs
- **[MITRE CVE](https://cve.mitre.org/)** — Authoritative catalog of publicly disclosed vulnerabilities (IDs + descriptions + refs).
- **[NVD (National Vulnerability Database)](https://nvd.nist.gov/vuln/data-feeds)** — Enriched CVE analytics (CVSS, CWE, CPE); maintains the **[CPE dictionary](https://nvd.nist.gov/products/cpe)**.
- **[ZDI Advisories](https://www.zerodayinitiative.com/advisories/published/)** — Zero Day Initiative disclosures with CVE/assessment details.
- **[GitHub Security Advisories (GHSA)](https://github.com/advisories)** — CVEs + GHSA entries; often includes CVSS/CWE and affected package ranges.

### Exploitation & prioritization
- **[CISA Known Exploited Vulnerabilities (KEV)](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)** — CVEs confirmed exploited in the wild; excellent for prioritization.
- **[Rapid7 AttackerKB](https://attackerkb.com/)** — Community assessments and exploitability/impact signals.
- **[OffSec Exploit-DB](https://www.exploit-db.com/)** — Public exploits/PoCs mapped to CVEs.

### Knowledge bases & taxonomies
- **[MITRE CWE](https://cwe.mitre.org/)** — Weakness taxonomy (root-cause mapping).
- **[MITRE CAPEC](https://capec.mitre.org/)** — Attack pattern dictionary.
- **[MITRE ATT&CK](https://attack.mitre.org/)** — Tactics/techniques knowledge base.
- **[MITRE D3FEND](https://d3fend.mitre.org/)** — Defensive countermeasure knowledge base.

### Mailing lists (archives)
- **[Bugtraq](https://seclists.org/bugtraq/)** — Historical disclosures (ended 2021).
- **[Full-Disclosure](https://seclists.org/fulldisclosure/)** — Community disclosures/discussion.
- **[OSS-Security](https://www.openwall.com/lists/oss-security/)** — Open-source security issues.
- **[Linux-CVE-Announce](https://lore.kernel.org/linux-cve-announce/)** — Linux kernel CVE announcements.

### Patch sources
- **[GitHub](https://github.com/)** — fetch patch content when the NVD entry includes a reference tagged **patch** that points to GitHub.
- **[git.kernel.org](https://git.kernel.org/)** — fetch patch content when the NVD entry includes a reference tagged **patch** that points to kernel.org.

### JSONL (2 generic examples)

```
{"source":"NVD","source_id":"CVE-2024-0001","title":"Example vuln in XYZ","description":"Buffer overflow in XYZ component allows RCE.","published_at":"2024-02-10T09:00:00Z","modified_at":"2024-02-12T12:30:00Z","cve_ids":["CVE-2024-0001"],"cwe_ids":["CWE-120"],"cvss_base":9.8,"cvss_vector":"CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H","severity":"CRITICAL","affected_products":["cpe:2.3:a:vendor:xyz:1.2:*:*:*:*:*:*:*"],"exploited_in_the_wild":false,"exploit_refs":["https://www.exploit-db.com/exploits/00000"],"patch_refs":["https://github.com/vendor/xyz/commit/abc123"],"references":["https://nvd.nist.gov/vuln/detail/CVE-2024-0001"],"tags":["overflow","rce"],"license":"See source","retrieved_at":"2025-10-02T00:00:00Z"}
{"source":"GHSA","source_id":"GHSA-aaaa-bbbb","title":"Example package vuln","description":"Improper input validation in package `foo`.","published_at":"2025-03-05T14:00:00Z","modified_at":null,"cve_ids":["CVE-2025-1111"],"cwe_ids":["CWE-20"],"cvss_base":7.5,"cvss_vector":"CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:N","severity":"HIGH","affected_products":["pkg:npm/foo@2.3.1"],"exploited_in_the_wild":false,"exploit_refs":[],"patch_refs":["https://github.com/org/foo/commit/def456"],"references":["https://github.com/advisories/GHSA-aaaa-bbbb"],"tags":["input-validation"],"license":"See source","retrieved_at":"2025-10-02T00:00:00Z"}
```

## Implementation

### Crawling strategies
- Use official feeds and mailing-list archives; fetch updates incrementally (deltas) instead of reprocessing history.
- Schedule periodic downloads for stable catalogs (e.g., CPE dictionary, KEV, CWE, CAPEC, D3FEND).
- For mailing lists, traverse archive indexes and fetch each message for processing.
- Extract referenced advisories/patches from vulnerability records for downstream relation mining.

### Pipeline schema (stages)
| Stage | Purpose | Inputs (examples) | Actions | Outputs |
|---|---|---|---|---|
| Source Validation | verify links and availability | all sources | check URL/status before processing | valid source list |
| Data Fetching | incremental fetch of new/changed data | validated sources | pull only deltas (since last run) | raw payloads |
| Data Filtering | remove non-vuln noise | raw payloads | drop README/CHANGELOG/etc. | filtered set |
| Data Deduplication | collapse duplicates | filtered set | exact-match dedup across sources | unique items |
| Format Unification | single interface | unique items | normalize to JSON records | unified JSON |
| Relation Mining | connect entities | unified JSON | derive links (CVEs ↔ advisories ↔ exploits ↔ patches ↔ products ↔ taxonomies) | relations JSON |
| Statistical Analysis | summarize dataset | unified JSON | compute counts/metrics | stats JSON/CSV |

### Source Validation
Validate that referenced links resolve before processing. Mailing lists and NVD references often include invalid or unreachable URLs; discard those early.

### Data Fetching
Fetch only new or changed items since the last run from each source to avoid reprocessing historical data.

### Data Filtering
Remove non-vulnerability noise (e.g., README/CHANGELOG and other unrelated files) and keep only vulnerability-related content.

### Data Deduplication
Collapse exact duplicate records that appear across multiple sources.

### Format Unification
Normalize all kept items into a unified JSON record format to provide a single interface for downstream use.

### Relation Mining
Derive links across records (CVEs ↔ advisories ↔ exploits ↔ patches ↔ products ↔ taxonomies).  
Expected relationships to include:
- CVE ↔ CPE, CVE ↔ CWE, CVE ↔ CVSS, CVE ↔ KEV, CVE ↔ AttackerKB, CVE ↔ Exploit-DB (PoC), CVE ↔ Mail, CVE ↔ Patch
- CWE ↔ CAPEC, CAPEC ↔ ATT&CK, ATT&CK ↔ D3FEND

### Statistical Analysis
Compute summary counts/metrics over the unified dataset after relation mining.
