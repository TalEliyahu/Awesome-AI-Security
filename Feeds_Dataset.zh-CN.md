[English](Feeds_Dataset.md) | 简体中文

> 说明：本中文对应版保留资源官方名称、链接和原有排序，便于与英文版对照维护。

### 漏洞与威胁情报（实时源 → 统一数据集规范） <a name="vulnerability--threat-intelligence-live-feeds--unified-dataset-spec"></a>

> 这些是**实时来源**，不是静态数据转储。可使用下面的模式构建单一、去重的数据集（CSV/Parquet/JSONL），用于 AI 安全研究、资源整理和仪表板。

### 规范化模式（推荐）
| 字段 | 类型 | 描述 |
|---|---|---|
| `source` | string | Feed 或系统名称，例如 `MITRE_CVE`、`NVD`、`GHSA`、`ZDI`、`KEV`、`CWE`、`CAPEC`、`MITRE_ATTACK`、`D3FEND`、`AttackerKB`、`ExploitDB`、`Bugtraq`、`FullDisclosure`、`oss-security`、`Linux-CVE-Announce`、`GitHub`、`git.kernel.org` |
| `source_id` | string | 来源内的主标识，例如 CVE-ID、GHSA-ID、ZDI-ID、消息 URL 或提交哈希 |
| `title` | string | 记录标题或主题 |
| `description` | string | 简短摘要（Markdown 或纯文本） |
| `published_at` | datetime | 来源首次发布时间戳 |
| `modified_at` | datetime | 最后更新时间戳（如有） |
| `cve_ids` | array\<string> | 引用的 CVE（0..n） |
| `cwe_ids` | array\<string> | 引用的 CWE（0..n） |
| `cvss_base` | float | CVSS 基础分（优先使用 v3.x） |
| `cvss_vector` | string | CVSS 向量，例如 `CVSS:3.1/...` |
| `severity` | enum | `CRITICAL|HIGH|MEDIUM|LOW|UNKNOWN`（按来源规范化） |
| `affected_products` | array\<string> | 优先使用 CPE 名称（`cpe:2.3:...`）或 purl（`pkg:`） |
| `exploited_in_the_wild` | boolean | 如果列入 KEV 或来源声明已被野外利用，则为 true |
| `exploit_refs` | array\<string> | PoC 或漏洞利用链接，例如 Exploit-DB、gist |
| `patch_refs` | array\<string> | 提交、发布版本或厂商公告链接 |
| `references` | array\<string> | 记录引用的其他参考资料或 URL |
| `tags` | array\<string> | 自由标签，例如 `deserialization`、`RCE`、`kernel` |
| `license` | string | 来源许可或使用条款（如可用） |
| `retrieved_at` | datetime | 爬虫抓取时间 |

### 数据集类别
- **CVE Record** — 从多个数据库（如 MITRE、NVD、ZDI、GitHub）聚合的 CVE 条目。
- **Assessment** — 与 CVE 相关的信号/元数据（如 CPE、CVSS、KEV、AttackerKB）以及分类法（CWE、CAPEC、ATT&CK、D3FEND）。
- **PoC** — 漏洞利用或概念验证（可运行代码或复现步骤）。
- **Mail** — 与一个或多个 CVE 相关的邮件列表消息或线程。
- **Patch** — 来自提交的代码差异，可附带提交消息。

### 核心 CVE 数据库与目录
- **[MITRE CVE](https://cve.mitre.org/)** — 公开披露漏洞的权威目录（ID、描述和参考链接）。
- **[NVD (National Vulnerability Database)](https://nvd.nist.gov/vuln/data-feeds)** — 增强的 CVE 分析数据（CVSS、CWE、CPE）；维护 **[CPE 字典](https://nvd.nist.gov/products/cpe)**。
- **[ZDI Advisories](https://www.zerodayinitiative.com/advisories/published/)** — Zero Day Initiative 披露内容，包含 CVE 与评估细节。
- **[GitHub Security Advisories (GHSA)](https://github.com/advisories)** — CVE 与 GHSA 条目，通常包含 CVSS/CWE 和受影响包范围。

### 利用与优先级排序
- **[CISA Known Exploited Vulnerabilities (KEV)](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)** — 已确认被野外利用的 CVE，适合用于优先级排序。
- **[Rapid7 AttackerKB](https://attackerkb.com/)** — 社区评估以及可利用性/影响信号。
- **[OffSec Exploit-DB](https://www.exploit-db.com/)** — 映射到 CVE 的公开漏洞利用和 PoC。

### 知识库与分类法
- **[MITRE CWE](https://cwe.mitre.org/)** — 弱点分类法（根因映射）。
- **[MITRE CAPEC](https://capec.mitre.org/)** — 攻击模式字典。
- **[MITRE ATT&CK](https://attack.mitre.org/)** — 战术/技术知识库。
- **[MITRE D3FEND](https://d3fend.mitre.org/)** — 防御对策知识库。

### 邮件列表（归档）
- **[Bugtraq](https://seclists.org/bugtraq/)** — 历史漏洞披露（2021 年停止）。
- **[Full-Disclosure](https://seclists.org/fulldisclosure/)** — 社区披露与讨论。
- **[OSS-Security](https://www.openwall.com/lists/oss-security/)** — 开源安全问题。
- **[Linux-CVE-Announce](https://lore.kernel.org/linux-cve-announce/)** — Linux 内核 CVE 公告。

### 补丁来源
- **[GitHub](https://github.com/)** — 当 NVD 条目包含指向 GitHub 且标记为 **patch** 的参考链接时，抓取补丁内容。
- **[git.kernel.org](https://git.kernel.org/)** — 当 NVD 条目包含指向 kernel.org 且标记为 **patch** 的参考链接时，抓取补丁内容。

### JSONL（2 个通用示例）

```
{"source":"NVD","source_id":"CVE-2024-0001","title":"Example vuln in XYZ","description":"Buffer overflow in XYZ component allows RCE.","published_at":"2024-02-10T09:00:00Z","modified_at":"2024-02-12T12:30:00Z","cve_ids":["CVE-2024-0001"],"cwe_ids":["CWE-120"],"cvss_base":9.8,"cvss_vector":"CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H","severity":"CRITICAL","affected_products":["cpe:2.3:a:vendor:xyz:1.2:*:*:*:*:*:*:*"],"exploited_in_the_wild":false,"exploit_refs":["https://www.exploit-db.com/exploits/00000"],"patch_refs":["https://github.com/vendor/xyz/commit/abc123"],"references":["https://nvd.nist.gov/vuln/detail/CVE-2024-0001"],"tags":["overflow","rce"],"license":"See source","retrieved_at":"2025-10-02T00:00:00Z"}
{"source":"GHSA","source_id":"GHSA-aaaa-bbbb","title":"Example package vuln","description":"Improper input validation in package `foo`.","published_at":"2025-03-05T14:00:00Z","modified_at":null,"cve_ids":["CVE-2025-1111"],"cwe_ids":["CWE-20"],"cvss_base":7.5,"cvss_vector":"CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:N","severity":"HIGH","affected_products":["pkg:npm/foo@2.3.1"],"exploited_in_the_wild":false,"exploit_refs":[],"patch_refs":["https://github.com/org/foo/commit/def456"],"references":["https://github.com/advisories/GHSA-aaaa-bbbb"],"tags":["input-validation"],"license":"See source","retrieved_at":"2025-10-02T00:00:00Z"}
```

## 实施

### 爬取策略
- 使用官方源和邮件列表归档；以增量方式抓取更新，避免重复处理历史数据。
- 对稳定目录（如 CPE 字典、KEV、CWE、CAPEC、D3FEND）安排周期性下载。
- 对邮件列表，遍历归档索引并抓取每条消息进行处理。
- 从漏洞记录中提取引用的公告和补丁，用于下游关系挖掘。

### 流水线模式（阶段）
| 阶段 | 目的 | 输入（示例） | 动作 | 输出 |
|---|---|---|---|---|
| 来源验证 | 验证链接与可用性 | 所有来源 | 处理前检查 URL/状态 | 有效来源列表 |
| 数据抓取 | 增量抓取新增/变更数据 | 已验证来源 | 仅拉取自上次运行后的增量 | 原始载荷 |
| 数据过滤 | 移除非漏洞噪声 | 原始载荷 | 丢弃 README/CHANGELOG 等内容 | 过滤后的集合 |
| 数据去重 | 合并重复项 | 过滤后的集合 | 跨来源精确匹配去重 | 唯一条目 |
| 格式统一 | 提供单一接口 | 唯一条目 | 规范化为 JSON 记录 | 统一 JSON |
| 关系挖掘 | 连接实体 | 统一 JSON | 推导链接（CVE ↔ 公告 ↔ 利用 ↔ 补丁 ↔ 产品 ↔ 分类法） | 关系 JSON |
| 统计分析 | 汇总数据集 | 统一 JSON | 计算数量和指标 | 统计 JSON/CSV |

### 来源验证
处理前验证引用链接是否可访问。邮件列表和 NVD 参考链接常包含无效或不可达 URL，应尽早丢弃。

### 数据抓取
从每个来源仅抓取自上次运行以来新增或变更的条目，避免重复处理历史数据。

### 数据过滤
移除非漏洞噪声（如 README/CHANGELOG 和其他无关文件），仅保留与漏洞相关的内容。

### 数据去重
合并出现在多个来源中的完全重复记录。

### 格式统一
将所有保留条目规范化为统一 JSON 记录格式，为下游使用提供单一接口。

### 关系挖掘
推导记录之间的链接（CVE ↔ 公告 ↔ 利用 ↔ 补丁 ↔ 产品 ↔ 分类法）。

### 统计分析
在关系挖掘后，对统一数据集计算汇总数量和指标。
