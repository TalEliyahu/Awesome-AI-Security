# Awesome AI Security ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

Curated resources, research, and tools for securing AI systems.

---

## Table of Contents

- [Best Practices and Security Standards](#best-practices-and-security-standards)
  - [Governance & Management Frameworks](#governance--management-frameworks)
  - [Standards, Controls & Top 10s](#standards-controls--top-10s)
  - [Testing & Red Teaming](#testing--red-teaming)
  - [Implementation Guides & Best Practices](#implementation-guides--best-practices)
  - [Agentic Systems — Governance, Standards & Guides](#agentic-systems--governance-standards--guides)
- [Tools](#tools)
- [Attack & Defense Matrices](#attack--defense-matrices)
  - [Attack](#attack)
  - [Defense](#defense)
- [Checklists](#checklists)
- [Foundations: Glossary, SoK/Surveys & Taxonomies](#foundations-glossary-soksurveys--taxonomies)
  - [Glossary](#glossary)
  - [SoK & Surveys](#sok--surveys)
  - [Taxonomy](#taxonomy)
- [Datasets](#datasets)
- [Courses & Certifications](#courses--certifications)
  - [Career Pathways](#career-pathways)
  - [Courses (includes labs)](#courses-includes-labs)
  - [Professional Certifications (exam-based)](#professional-certifications-exam-based)
- [Training](#training)
  - [Provider Training Portals](#provider-training-portals)
  - [Guided Tracks](#guided-tracks)
  - [CTFs & Challenges](#ctfs--challenges)
  - [Bespoke](#bespoke)
- [Research Working Groups](#research-working-groups)
- [Communities & Social Groups](#communities--social-groups)
- [Benchmarking](#benchmarking)
- [Incident Response](#incident-response)
  - [Incident Repositories, Trackers & Monitors](#incident-repositories-trackers--monitors)
  - [Guides & Playbooks](#guides--playbooks)
- [Supply Chain Security](#supply-chain-security)
  - [Standards & Specs](#standards--specs)
  - [Third-Party Assessment](#third-party-assessment)
- [Newsletter](#newsletter)
- [Conferences](https://github.com/TalEliyahu/Awesome-AI-Security/blob/main/Conferences.md)
- [Reports and Research](#reports-and-research)
  - [Research Feed](#research-feed)
  - [Reports](#reports)
- [CTFs & Challenges](#ctfs--challenges)
- [Podcasts](#podcasts)
- [Market Landscape](#market-landscape)
- [Startups Blogs](#startups-blogs)
- [Related Awesome Lists](#related-awesome-lists)
- [Common Acronyms](#common-acronyms)

---

## Best Practices and Security Standards

### Governance & Management Frameworks
- [NIST — AI Risk Management Framework (AI RMF)](https://www.nist.gov/itl/ai-risk-management-framework)
- [ISO/IEC 42001 (AI Management System)](https://www.iso.org/standard/81230.html)
- [OWASP — AI Maturity Assessment (AIMA)](https://github.com/OWASP/www-project-ai-maturity-assessment) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-ai-maturity-assessment?logo=github&label=&style=social)](https://github.com/OWASP/www-project-ai-maturity-assessment)
- [Google — Secure AI Framework (SAIF)](https://saif.google/)
- [OWASP — LLM & GenAI Security Center of Excellence (CoE) Guide](https://genai.owasp.org/resource/llm-and-generative-ai-security-center-of-excellence-guide/)
- [CSA — AI Model Risk Management Framework](https://cloudsecurityalliance.org/artifacts/ai-model-risk-management-framework)
- [NIST — Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) 

### Standards, Controls & Top 10s

#### Controls & Verification Standards
- [OWASP — LLM Security Verification Standard (LLMSVS)](https://github.com/OWASP/www-project-llm-verification-standard) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-llm-verification-standard?logo=github&label=&style=social)](https://github.com/OWASP/www-project-llm-verification-standard)
- [OWASP — Artificial Intelligence Security Verification Standard (AISVS)](https://github.com/OWASP/AISVS) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/AISVS?logo=github&label=&style=social)](https://github.com/OWASP/AISVS)
- [CSA — AI Controls Matrix (AICM)](https://cloudsecurityalliance.org/artifacts/ai-controls-matrix) — The AICM contains 243 control objectives across 18 domains and maps to ISO 42001, ISO 27001, NIST AI RMF 1.0, and BSI AIC4. Freely downloadable.

#### Top 10s
- [OWASP — Top 10 for Large Language Model Applications](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-top-10-for-large-language-model-applications?logo=github&label=&style=social)](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications)
- [CSA - MCP Client Top 10](https://modelcontextprotocol-security.io/top10/client/) 
- [CSA - MCP Server Top 10](https://modelcontextprotocol-security.io/top10/server/)

#### Scoring & Rating Systems
- [OWASP — Artificial Intelligence Vulnerability Scoring System](https://github.com/OWASP/www-project-artificial-intelligence-vulnerability-scoring-system) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-artificial-intelligence-vulnerability-scoring-system?logo=github&label=&style=social)](https://github.com/OWASP/www-project-artificial-intelligence-vulnerability-scoring-system)

### Testing & Red Teaming
- [OWASP — AI Testing Guide](https://github.com/OWASP/www-project-ai-testing-guide) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-ai-testing-guide?logo=github&label=&style=social)](https://github.com/OWASP/www-project-ai-testing-guide)
- [OWASP — Red Teaming Guide](https://genai.owasp.org/resource/genai-red-teaming-guide/)
- [OWASP — LLM Exploit Generation](https://genai.owasp.org/resource/owasp-llm-exploit-generation-v1-0-pdf/)
- [CSA — Agentic AI Red Teaming Guide](https://cloudsecurityalliance.org/artifacts/agentic-ai-red-teaming-guide)

### Implementation Guides & Best Practices
- [OWASP — AI Security and Privacy Guide](https://github.com/OWASP/www-project-ai-security-and-privacy-guide) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-ai-security-and-privacy-guide?logo=github&label=&style=social)](https://github.com/OWASP/www-project-ai-security-and-privacy-guide)
- [OWASP — LLM and Gen AI Data Security Best Practices](https://genai.owasp.org/resource/llm-and-gen-ai-data-security-best-practices/)
- [OWASP — GenAI Security Project](https://github.com/OWASP/genai-security-project) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/genai-security-project?logo=github&label=&style=social)](https://github.com/OWASP/genai-security-project)
- [CSA — Secure LLM Systems: Essential Authorization Practices](https://cloudsecurityalliance.org/artifacts/securing-llm-backed-systems-essential-authorization-practices)
- [NIST — Four Principles of Explainable Artificial Intelligence](https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=933399)
- [OASIS CoSAI — Preparing Defenders of AI Systems](https://github.com/cosai-oasis/ws2-defenders/blob/main/preparing-defenders-of-ai-systems.md) [![GitHub Repo stars](https://img.shields.io/github/stars/cosai-oasis/ws2-defenders?logo=github&label=&style=social)](https://github.com/cosai-oasis/ws2-defenders)
- [CISA — AI Data Security: Best Practices for Securing Data Used to Train & Operate AI Systems](https://www.cisa.gov/news-events/alerts/2025/05/22/new-best-practices-guide-securing-ai-data-released)
- [DoD CIO — AI Cybersecurity Risk Management Tailoring Guide (2025)](https://dodcio.defense.gov/Portals/0/Documents/Library/AI-CybersecurityRMTailoringGuide.pdf) — Practical RMF tailoring for AI systems across the lifecycle; complements CDAO’s RAI toolkit.


### Agentic Systems — Governance, Standards & Guides
- [OWASP — Agent Observability Standard (AOS)](https://github.com/OWASP/www-project-agent-observability-standard) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-agent-observability-standard?logo=github&label=&style=social)](https://github.com/OWASP/www-project-agent-observability-standard)
- [OWASP — Agent Name Service (ANS) for Secure AI Agent Discovery](https://genai.owasp.org/resource/agent-name-service-ans-for-secure-al-agent-discovery-v1-0/)
- [OWASP — Agentic AI - Threats and Mitigations](https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/)
- [OWASP — Securing Agentic Applications Guide](https://genai.owasp.org/resource/securing-agentic-applications-guide-1-0/)
- [OWASP — Multi-Agentic System Threat Modeling Guide](https://genai.owasp.org/resource/multi-agentic-system-threat-modeling-guide-v1-0/)
- [OWASP — State of Agentic AI Security and Governance](https://genai.owasp.org/resource/state-of-agentic-ai-security-and-governance-1-0/)
- [CSA — Secure Agentic System Design: A Trait-Based Approach](https://cloudsecurityalliance.org/artifacts/secure-agentic-system-design)
- [CSA — Agentic AI Identity & Access Management](https://cloudsecurityalliance.org/artifacts/agentic-ai-identity-and-access-management-a-new-approach) — 08/25

---

## Tools
*Inclusion criteria (open-source tools): must have **220+ GitHub stars**, **active maintenance in the last 12 months**, and **≥3 contributors**.*

### Prompt-Injection Detection & Mitigation
*Detect and stop prompt-injection (direct/indirect) across inputs, context, and outputs; filter hostile content before it reaches tools or models.*

- *(none from your current list yet)*

### Jailbreak & Policy Enforcement (Guardrails)
*Enforce safety policies and block jailbreaks at runtime via rules/validators/DSLs, with optional human-in-the-loop for sensitive actions.*

- **[NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)** [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails?logo=github&label=&style=social)](https://github.com/NVIDIA/NeMo-Guardrails)
- **[LLM Guard](https://github.com/protectai/llm-guard)** [![GitHub Repo stars](https://img.shields.io/github/stars/protectai/llm-guard?logo=github&label=&style=social)](https://github.com/protectai/llm-guard)
- **[Llama Guard](https://github.com/meta-llama/PurpleLlama/tree/main/Llama-Guard4)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama)
- **[LlamaFirewall](https://github.com/meta-llama/PurpleLlama/tree/main/LlamaFirewall)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama)
- **[Code Shield](https://github.com/meta-llama/PurpleLlama/tree/main/CodeShield)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama)
- **[Guardrails](https://github.com/guardrails-ai/guardrails)** [![GitHub Repo stars](https://img.shields.io/github/stars/guardrails-ai/guardrails?logo=github&label=&style=social)](https://github.com/guardrails-ai/guardrails) — Runtime policy enforcement for LLM apps: compose input/output validators (PII, toxicity, jailbreak/PI, regex, competitor checks), then block/redact/rewrite/retry on fail; optional server mode; also supports structured outputs (Pydantic/function-calling).


### Model Artifact Scanners
*Analyze serialized model files for unsafe deserialization and embedded code; verify integrity/metadata and **block or quarantine on fail**.*

- **[ModelScan](https://github.com/protectai/modelscan)** [![GitHub Repo stars](https://img.shields.io/github/stars/protectai/modelscan?logo=github&label=&style=social)](https://github.com/protectai/modelscan)
- **[Fickling](https://github.com/trailofbits/fickling)** [![GitHub Repo stars](https://img.shields.io/github/stars/trailofbits/fickling?logo=github&label=&style=social)](https://github.com/trailofbits/fickling)
- **[picklescan](https://github.com/mmaitre314/picklescan)** [![GitHub Repo stars](https://img.shields.io/github/stars/mmaitre314/picklescan?logo=github&label=&style=social)](https://github.com/mmaitre314/picklescan)

### Agent Tooling and MCP Security
*Scan/audit MCP servers & client configs; detect tool poisoning, unsafe flows; constrain tool access with least-privilege and audit trails.*

#### Honeypots & Deception (MCP/LLM)

- **[Beelzebub](https://github.com/mariocandela/beelzebub)** [![GitHub Repo stars](https://img.shields.io/github/stars/mariocandela/beelzebub?logo=github&label=&style=social)](https://github.com/mariocandela/beelzebub) — Beelzebub is a honeypot framework designed to provide a secure environment for detecting and analyzing cyber attacks. It offers a low code approach for easy implementation and uses AI to mimic the behavior of a high-interaction honeypot.

#### Tool manifest/metadata validators
- **[MCP Inspector](https://github.com/modelcontextprotocol/inspector)** [![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector?logo=github&label=&style=social)](https://github.com/modelcontextprotocol/inspector)
- **[mcp-scan](https://github.com/invariantlabs-ai/mcp-scan)** [![GitHub Repo stars](https://img.shields.io/github/stars/invariantlabs-ai/mcp-scan?logo=github&label=&style=social)](https://github.com/invariantlabs-ai/mcp-scan)

#### Servers & Dev tooling
- **[PortSwigger — MCP Server](https://github.com/PortSwigger/mcp-server)** [![GitHub Repo stars](https://img.shields.io/github/stars/PortSwigger/mcp-server?logo=github&label=&style=social)](https://github.com/PortSwigger/mcp-server)

### Execution Sandboxing for Agent Code
*Run untrusted or LLM-triggered code in isolated sandboxes (FS/network/process limits) to contain RCE and reduce blast radius.*

- **[E2B](https://github.com/e2b-dev/E2B)** [![GitHub Repo stars](https://img.shields.io/github/stars/e2b-dev/E2B?logo=github&label=&style=social)](https://github.com/e2b-dev/E2B) — SDK + self-hostable infra to run untrusted, LLM-generated code in isolated cloud sandboxes (Firecracker microVMs).

### Gateways & Policy Proxies
*Centralize auth, quotas/rate limits, cost caps, egress/DLP filters, and guardrail orchestration across all model/providers.*

- *(none from your current list yet)*

### Code Review
- **[Claude Code Security Reviewer](https://github.com/anthropics/claude-code-security-review)** [![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/claude-code-security-review?logo=github&label=&style=social)](https://github.com/anthropics/claude-code-security-review) - An AI-powered security review GitHub Action using Claude to analyze code changes for security vulnerabilities.
- **[Vulnhuntr](https://github.com/protectai/vulnhuntr)** [![GitHub Repo stars](https://img.shields.io/github/stars/protectai/vulnhuntr?logo=github&label=&style=social)](https://github.com/protectai/vulnhuntr) - Vulnhuntr leverages the power of LLMs to automatically create and analyze entire code call chains starting from remote user input and ending at server output for detection of complex, multi-step, security-bypassing vulnerabilities that go far beyond what traditional static code analysis tools are capable of performing.
  
### Red-Teaming Harnesses & Automated Security Testing
*Automate attack suites (prompt-injection, leakage, jailbreak, goal-based tasks) in CI; score results and produce regression evidence.*

#### Prompt-injection test suites
- **[Promptmap](https://github.com/utkusen/promptmap)** [![GitHub Repo stars](https://img.shields.io/github/stars/utkusen/promptmap?logo=github&label=&style=social)](https://github.com/utkusen/promptmap)
- **[Giskard](https://github.com/Giskard-AI/giskard)** [![GitHub Repo stars](https://img.shields.io/github/stars/Giskard-AI/giskard?logo=github&label=&style=social)](https://github.com/Giskard-AI/giskard)

#### Data-leakage/secret-exfil test suites
- **[garak](https://github.com/NVIDIA/garak)** [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/garak?logo=github&label=&style=social)](https://github.com/NVIDIA/garak)
- **[Agentic Security](https://github.com/msoedov/agentic_security)** [![GitHub Repo stars](https://img.shields.io/github/stars/msoedov/agentic_security?logo=github&label=&style=social)](https://github.com/msoedov/agentic_security)

#### Jailbreak catalogs & adversarial prompts
- **[FuzzyAI](https://github.com/cyberark/FuzzyAI)** [![GitHub Repo stars](https://img.shields.io/github/stars/cyberark/FuzzyAI?logo=github&label=&style=social)](https://github.com/cyberark/FuzzyAI)
- **[GPTFuzz](https://github.com/sherdencooper/GPTFuzz)** [![GitHub Repo stars](https://img.shields.io/github/stars/sherdencooper/GPTFuzz?logo=github&label=&style=social)](https://github.com/sherdencooper/GPTFuzz)

#### Adversarial-robustness (evasion) toolkits
- **[TextAttack](https://github.com/QData/TextAttack)** [![GitHub Repo stars](https://img.shields.io/github/stars/QData/TextAttack?logo=github&label=&style=social)](https://github.com/QData/TextAttack)
- **[Foolbox](https://github.com/bethgelab/foolbox)** [![GitHub Repo stars](https://img.shields.io/github/stars/bethgelab/foolbox?logo=github&label=&style=social)](https://github.com/bethgelab/foolbox)

#### Goal-directed agent attack tasks
- **[PyRIT](https://github.com/Azure/PyRIT)** [![GitHub Repo stars](https://img.shields.io/github/stars/Azure/PyRIT?logo=github&label=&style=social)](https://github.com/Azure/PyRIT)
- **[AgentDojo](https://github.com/ethz-spylab/agentdojo)** [![GitHub Repo stars](https://img.shields.io/github/stars/ethz-spylab/agentdojo?logo=github&label=&style=social)](https://github.com/ethz-spylab/agentdojo)
- **[PentestGPT](https://github.com/GreyDGL/PentestGPT)** [![GitHub Repo stars](https://img.shields.io/github/stars/GreyDGL/PentestGPT?logo=github&label=&style=social)](https://github.com/GreyDGL/PentestGPT)
- **[CAI — Cybersecurity AI](https://github.com/aliasrobotics/cai)** [![GitHub Repo stars](https://img.shields.io/github/stars/aliasrobotics/cai?logo=github&label=&style=social)](https://github.com/aliasrobotics/cai) 
- **[hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT)** [![GitHub Repo stars](https://img.shields.io/github/stars/ipa-lab/hackingBuddyGPT?logo=github&label=&style=social)](https://github.com/ipa-lab/hackingBuddyGPT)
- **[HexStrike AI](https://github.com/0x4m4/hexstrike-ai)** [![GitHub Repo stars](https://img.shields.io/github/stars/0x4m4/hexstrike-ai?logo=github&label=&style=social)](https://github.com/0x4m4/hexstrike-ai)
- **[Nebula](https://github.com/berylliumsec/nebula)** [![GitHub Repo stars](https://img.shields.io/github/stars/berylliumsec/nebula?logo=github&label=&style=social)](https://github.com/berylliumsec/nebula)

#### CI pipelines & regression gates
- **[promptfoo](https://github.com/promptfoo/promptfoo)** [![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?logo=github&label=&style=social)](https://github.com/promptfoo/promptfoo)
- **[Agentic Radar](https://github.com/splx-ai/agentic-radar)** [![GitHub Repo stars](https://img.shields.io/github/stars/splx-ai/agentic-radar?logo=github&label=&style=social)](https://github.com/splx-ai/agentic-radar)
- **[DeepTeam](https://github.com/confident-ai/deepteam)** [![GitHub Repo stars](https://img.shields.io/github/stars/confident-ai/deepteam?logo=github&label=&style=social)](https://github.com/confident-ai/deepteam)
- **[Buttercup](https://github.com/trailofbits/buttercup)** [![GitHub Repo stars](https://img.shields.io/github/stars/trailofbits/buttercup?logo=github&label=&style=social)](https://github.com/trailofbits/buttercup) — Trail of Bits’ AIxCC Cyber Reasoning System: runs OSS-Fuzz–style campaigns to find vulns, then uses a multi-agent LLM patcher to generate & validate fixes for C/Java repos; ships SigNoz observability; requires at least one LLM API key.

#### Scoring/leaderboards & evidence reports
- *(none from your current list yet)*

### Supply Chain: AI/ML BOM and Attestation
*Generate and verify AI/ML BOMs, signatures, and provenance for models/datasets/dependencies; enforce allow/deny policies.*

- *(none from your current list yet)*

### Vector/Memory Store Security
*Harden RAG memory: isolate namespaces, sanitize queries/content, detect poisoning/outliers, and prevent secret/PII retention.*

- *(none from your current list yet)*

### Data/Model Poisoning Defenses
*Detect and mitigate dataset/model poisoning and backdoors; validate training/fine-tuning integrity and prune suspicious behaviors.*

- **[Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)** [![GitHub Repo stars](https://img.shields.io/github/stars/Trusted-AI/adversarial-robustness-toolbox?logo=github&label=&style=social)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)

### Sensitive Data Leak Prevention (DLP for AI)
*Prevent secret/PII exfiltration in prompts/outputs via detection, redaction, and policy checks at I/O boundaries.*

- **[Presidio](https://github.com/microsoft/presidio)** [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/presidio?logo=github&label=&style=social)](https://github.com/microsoft/presidio) — PII/PHI detection & redaction for text, images, and structured data; use as a pre/post-LLM DLP filter and for dataset sanitization.

### Monitoring, Logging & Anomaly Detection
*Collect AI-specific security logs/signals; detect abuse patterns (PI/jailbreak/leakage), enrich alerts, and support forensics.*

- **[LangKit](https://github.com/whylabs/langkit)** [![GitHub Repo stars](https://img.shields.io/github/stars/whylabs/langkit?logo=github&label=&style=social)](https://github.com/whylabs/langkit) — LLM observability metrics toolkit (whylogs-compatible): prompt-injection/jailbreak similarity, PII patterns, hallucination/consistency, relevance, sentiment/toxicity, readability.

- **[Alibi Detect](https://github.com/SeldonIO/alibi-detect)** [![GitHub Repo stars](https://img.shields.io/github/stars/SeldonIO/alibi-detect?logo=github&label=&style=social)](https://github.com/SeldonIO/alibi-detect) — Production drift/outlier/adversarial detection for tabular, text, images, and time series; online/offline detectors with TF/PyTorch backends; returns scores, thresholds, and flags for alerting.


---

## Attack & Defense Matrices
*Matrix-style resources covering adversarial TTPs and curated defensive techniques for AI systems.*

### Attack
- [MITRE ATLAS](https://atlas.mitre.org) – Adversarial TTP matrix and knowledge base for threats to AI systems.
- [GenAI Attacks Matrix](https://ttps.ai/matrix.html#genai-attacks-matrix) – Matrix of TTPs targeting GenAI apps, copilots, and agents.
- [MCP Security Tactics, Techniques, and Procedures (TTPs)](https://modelcontextprotocol-security.io/ttps/)

### Defense
- [AIDEFEND — AI Defense Framework](https://github.com/edward-playground/aidefense-framework) [![GitHub Repo stars](https://img.shields.io/github/stars/edward-playground/aidefense-framework?logo=github&label=&style=social)](https://github.com/edward-playground/aidefense-framework) — Interactive defensive countermeasures knowledge base with Tactics / Pillars / Phases views; maps mitigations to MITRE ATLAS, MAESTRO, and OWASP LLM risks. • **Live demo:** https://edward-playground.github.io/aidefense-framework/

---

## Checklists

- [OWASP — LLM Applications Cybersecurity & Governance Checklist](https://genai.owasp.org/resource/llm-applications-cybersecurity-and-governance-checklist-english/)
- [SlowMist — MCP Security Checklist](https://github.com/slowmist/MCP-Security-Checklist) [![GitHub Repo stars](https://img.shields.io/github/stars/slowmist/MCP-Security-Checklist?logo=github&label=&style=social)](https://github.com/slowmist/MCP-Security-Checklist)

---

## Supply Chain Security
Guidance and standards for securing the AI/ML software supply chain (models, datasets, code, pipelines). Primarily specs and frameworks; includes vetted TPRM templates.

### Standards & Specs
*Normative formats and specifications for transparency and traceability across AI components and dependencies.*

- **OWASP — AI Bill of Materials (AIBOM)** [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-aibom?logo=github&label=&style=social)](https://github.com/OWASP/www-project-aibom) — Bill of materials format for AI components, datasets, and model dependencies.

### Third-Party Assessment
*Questionnaires and templates to assess external vendors, model providers, and integrators for security, privacy, and compliance.*

- **FS-ISAC — Generative AI Vendor Evaluation & Qualitative Risk Assessment** — [Assessment Tool XLSX](https://www.fsisac.com/hubfs/Knowledge/AI/FSISAC_GenerativeAI-VendorEvaluation&QualitativeRiskAssessmentTool.xlsx) • [Guide PDF](https://www.fsisac.com/hubfs/Knowledge/AI/FSISAC_GenerativeAI-VendorEvaluation&QualitativeRiskAssessment.pdf) — Vendor due-diligence toolkit for GenAI: risk tiering by use case, integration and data sensitivity; questionnaires across privacy, security, model development and validation, integration, legal and compliance; auto-generated reporting.

---

## Foundations: Glossary, SoK/Surveys & Taxonomies
*(Core references and syntheses for orientation and shared language.)*

### Glossary
*(Authoritative definitions for AI/ML security, governance, and risk—use to align terminology across docs and reviews.)*

- [**NIST — “The Language of Trustworthy AI: An In-Depth Glossary of Terms.”**](https://airc.nist.gov/glossary/) - Authoritative cross-org terminology aligned to NIST AI RMF; useful for standardizing terms across teams.
- [**ISO/IEC 22989:2022 — *Artificial intelligence — Concepts and terminology***](https://www.iso.org/standard/74296.html) - International standard that formalizes core AI concepts and vocabulary used in policy and engineering.

### SoK & Surveys
*(Systematizations of Knowledge (SoK), surveys, systematic reviews, and mapping studies.)*

### Taxonomy
*(Reusable classification schemes—clear dimensions, categories, and labeling rules for attacks, defenses, datasets, and risks.)*

- [**CSA — Large Language Model (LLM) Threats Taxonomy**](https://cloudsecurityalliance.org/artifacts/csa-large-language-model-llm-threats-taxonomy) - Community taxonomy of LLM-specific threats; clarifies categories/definitions for risk discussion and control mapping.
- [**ARC — PI (Prompt Injection) Taxonomy**](https://github.com/Arcanum-Sec/arc_pi_taxonomy) - Focused taxonomy for prompt-injection behaviors/variants with practical labeling guidance for detection and defense.
---

## Datasets

### Cybersecurity Skills 
Interactive CTFs and self-contained labs for hands-on security skills (web, pwn, crypto, forensics, reversing). **Used to** assess practical reasoning, tool use, and end-to-end task execution.

- **[NYU CTF Bench](https://github.com/NYU-LLM-CTF/LLM_CTF_Database)** [![GitHub Repo stars](https://img.shields.io/github/stars/NYU-LLM-CTF/LLM_CTF_Database?logo=github&label=&style=social)](https://github.com/NYU-LLM-CTF/LLM_CTF_Database)

### Cybersecurity Knowledge
Structured Q&A datasets assessing security knowledge and terminology. **Used to** evaluate factual recall and conceptual understanding.

- **[CyberMetric](https://github.com/CyberMetric)** [![GitHub Repo stars](https://img.shields.io/github/stars/CyberMetric?logo=github&label=&style=social)](https://github.com/CyberMetric)
 
### Secure Coding & Vulnerability Detection
Code snippet datasets labeled as vulnerable or secure, often tied to CWEs (Common Weakness Enumeration). **Used to** evaluate the model’s ability to recognize insecure code patterns and suggest secure fixes.

- **[LLMSecEval](https://github.com/tuhh-softsec/LLMSecEval)** [![GitHub Repo stars](https://img.shields.io/github/stars/tuhh-softsec/LLMSecEval?logo=github&label=&style=social)](https://github.com/tuhh-softsec/LLMSecEval)

- **[SecCodePLT](https://huggingface.co/datasets/Virtue-AI-HUB/SecCodePLT)** [![HF Downloads](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fdatasets%2FVirtue-AI-HUB%2FSecCodePLT&query=downloads&label=HF%20downloads&logo=huggingface)](https://huggingface.co/datasets/Virtue-AI-HUB/SecCodePLT)

### Jailbreak & Guardrail Evaluation
Adversarial prompt datasets—both text-only and multimodal—designed to bypass safety mechanisms or test refusal logic.
**Used to** test how effectively a model resists jailbreaks and enforces policy-based refusal.

- **[CySecBench](https://github.com/cysecbench/dataset)** [![GitHub Repo stars](https://img.shields.io/github/stars/cysecbench/dataset?logo=github&label=&style=social)](https://github.com/cysecbench/dataset)
- **[JailBreakV-28K](https://github.com/SaFoLab-WISC/JailBreakV_28K)** [![GitHub Repo stars](https://img.shields.io/github/stars/SaFoLab-WISC/JailBreakV_28K?logo=github&label=&style=social)](https://github.com/SaFoLab-WISC/JailBreakV_28K)
- **[Do-Not-Answer](https://github.com/Libr-AI/do-not-answer)** [![GitHub Repo stars](https://img.shields.io/github/stars/Libr-AI/do-not-answer?logo=github&label=&style=social)](https://github.com/Libr-AI/do-not-answer)

### Prompt Injection & Malicious Prompt Detection
Datasets labeled with whether prompts are benign or malicious (i.e., injection attempts).
**Used to** evaluate an LLM’s ability to detect and neutralize prompt-injection style attacks.

- **[Malicious Prompt Detection](https://github.com/AhsanAyub/malicious-prompt-detection)** [![GitHub Repo stars](https://img.shields.io/github/stars/AhsanAyub/malicious-prompt-detection?logo=github&label=&style=social)](https://github.com/AhsanAyub/malicious-prompt-detection)
- **[LLMail-Inject](https://github.com/microsoft/llmail-inject-challenge)** [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/llmail-inject-challenge?logo=github&label=&style=social)](https://github.com/microsoft/llmail-inject-challenge) 

---

## Courses & Certifications

#### Career Pathways
- **[SANS — AI Cybersecurity Careers](https://www.sans.org/cybersecurity-careers/)** — Career pathways poster + training map; baseline skills for AI security (IR, DFIR, detection, threat hunting).

#### Courses (includes labs)
- **[SANS — SEC545: GenAI & LLM Application Security](https://www.sans.org/cyber-security-courses/genai-llm-application-security)** — Hands-on course covering prompt injection, excessive agency, model supply chain, and defensive patterns. *(Certificate of completion provided by SANS.)*
- **[SANS — SEC495: Leveraging LLMs: Building & Securing RAG, Contextual RAG, and Agentic RAG](https://www.sans.org/cyber-security-courses/leveraging-llms-building-securing-rag)** — Practical RAG builds with threat modeling, validation, and guardrails. *(Certificate of completion provided by SANS.)*

#### Professional Certifications (exam-based)
- **[IAPP — Artificial Intelligence Governance Professional (AIGP)](https://iapp.org/certify/aigp/)** — Governance-focused credential aligned with emerging regulations.
- **[ISACA — Advanced in AI Security Management (AAISM™)](https://www.isaca.org/credentialing/aaism)** — AI-centric security management certification.
- **[NIST AI RMF 1.0 Architect — Certified Information Security](https://www.certifiedinfosec.com/services/training-courses/ai/nist-ai-rmf-1-0-architect-training)** — Credential aligned to NIST AI RMF 1.0.
- **[ISO/IEC 23894 — AI Risk Management (AI Risk Manager, PECB)](https://pecb.com/en/education-and-certification-for-individuals/ai-risk)** — Risk identification, assessment, and mitigation aligned to ISO/IEC 23894 and NIST AI RMF.
- **[ISO/IEC 42001 — AI Management System (Lead Implementer, PECB)](https://pecb.com/en/education-and-certification-for-individuals/iso-iec-42001/iso-iec-42001-lead-implementer)** — Implement an AIMS per ISO/IEC 42001.
- **[ISO/IEC 42001 — AI Management System (Lead Auditor, PECB)](https://pecb.com/en/education-and-certification-for-individuals/iso-iec-42001/iso-iec-42001-lead-auditor)** — Audit AIMS using recognized principles.
- **[ISACA — Advanced in AI Audit (AAIA™)](https://www.isaca.org/credentialing/aaia)** — Certification for auditing AI systems and mitigating AI-related risks.

---

## Training

### Provider Training Portals
- [Microsoft AI Security Learning Path](https://learn.microsoft.com/en-us/training/browse/?filter-roles=ai%20&roles=ai-engineer&subjects=security) — Free, self-paced Microsoft content on secure AI model development, risk management, and threat mitigation.
- [AWS AI Security Training](https://skillbuilder.aws/search?page=1&domain=artificial_intelligence&searchText=security) — Free AWS portal with courses on securing AI applications, risk management, and AI/ML security best practices.

### Guided Tracks
- [PortSwigger — Web Security Academy: Web LLM attacks](https://portswigger.net/web-security/llm-attacks) — Structured, guided track on LLM issues (prompt injection, insecure output handling, excessive agency) with walkthrough-style exercises.

### CTFs & Challenges
- [AI GOAT](https://github.com/dhammon/ai-goat) [![GitHub Repo stars](https://img.shields.io/github/stars/dhammon/ai-goat?logo=github&label=&style=social)](https://github.com/dhammon/ai-goat) — Vulnerable LLM CTF challenges for learning AI security.
- [Damn Vulnerable LLM Agent](https://github.com/ReversecLabs/damn-vulnerable-llm-agent) [![GitHub Repo stars](https://img.shields.io/github/stars/ReversecLabs/damn-vulnerable-llm-agent?logo=github&label=&style=social)](https://github.com/ReversecLabs/damn-vulnerable-llm-agent)
- [AI Red Teaming Playground Labs — Microsoft](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs) [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/AI-Red-Teaming-Playground-Labs?logo=github&label=&style=social)](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs) — Self-hostable environment with 12 challenges (direct/indirect prompt injection, metaprompt extraction, Crescendo multi-turn, guardrail bypass).

### Bespoke
- [Trail of Bits — AI/ML Security & Safety Training](https://www.trailofbits.com/services/software-assurance/ai-ml/) — Courses on AI failure modes, adversarial attacks, data provenance, pipeline threats, and mitigation.

---

## Research Working Groups

- [Cloud Security Alliance (CSA) AI Security Working Groups](https://cloudsecurityalliance.org/research/working-groups) – Collaborative research groups focused on AI security, cloud security, and emerging threats in AI-driven systems.
- [OWASP Top 10 for LLM & Generative AI Security Risks Project](https://genai.owasp.org/contribute/) – An open-source initiative addressing critical security risks in Large Language Models (LLMs) and Generative AI applications, offering resources and guidelines to mitigate emerging threats.
- [CWE Artificial Intelligence Working Group (AI WG)](https://cwe.mitre.org/community/working_groups.html) – The AI WG was established by CWE™ and CVE® community stakeholders to identify and address gaps in the CWE corpus where AI-related weaknesses are not adequately covered, and work collaboratively to fix them.
- [NIST — SP 800-53 Control Overlays for Securing AI Systems (COSAiS)](https://csrc.nist.gov/projects/cosais) – Public collaboration to develop AI security control overlays with NIST principal investigators and the community.
- [OpenSSF — AI/ML Security Working Group](https://github.com/ossf/ai-ml-security) — Cross-org WG on “security for AI” and “AI for security”
- [CoSAI — Coalition for Secure AI (OASIS Open Project)](https://github.com/cosai-oasis) — Open, cross-industry initiative advancing secure-by-design AI through shared frameworks, tooling, and guidance.
  - **WS1: Software Supply Chain Security for AI Systems** - Extends SSDF/SLSA principles to AI; provenance, model risks, and pipeline security.https://github.com/cosai-oasis/ws1-supply-chain
  - **WS2: Preparing Defenders for a Changing Cybersecurity Landscape** - Defender-focused framework aligning threats, mitigations, and investments for AI-driven ops. https://github.com/cosai-oasis/ws2-defenders  
    • Reference doc: “Preparing Defenders of AI Systems” https://github.com/cosai-oasis/ws2-defenders/blob/main/preparing-defenders-of-ai-systems.md
  - **WS3: AI Security Risk Governance** - Security-focused risk & controls taxonomy, checklist, and scorecard for AI products and components.https://github.com/cosai-oasis/ws3-ai-risk-governance
  - **WS4: Secure Design Patterns for Agentic Systems** - Threat models and secure design patterns for agentic systems and infrastructure. https://github.com/cosai-oasis/ws4-secure-design-agentic-systems

📌 *(More working groups to be added.)*

---

## Communities & Social Groups

- [AI Security Hub (LinkedIn Group)](https://www.linkedin.com/groups/14545517/)

---

## Benchmarking

### Benchmarks

- **[Purple Llama — CyberSecEval](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama)
- **[JailbreakBench](https://github.com/JailbreakBench/jailbreakbench)** [![GitHub Repo stars](https://img.shields.io/github/stars/JailbreakBench/jailbreakbench?logo=github&label=&style=social)](https://github.com/JailbreakBench/jailbreakbench)

### **Categories of AI Security Benchmarks**

#### **Robustness & Adversarial Resilience**  
**Purpose**: Evaluates how AI systems withstand adversarial attacks, including evasion, poisoning, and model extraction. Ensures AI remains functional under manipulation.  
**NIST AI RMF Alignment**: **Measure, Manage**  
- **Measure**: Identify risks related to adversarial attacks.  
- **Manage**: Implement mitigation strategies to ensure resilience.  

#### **Model & Data Integrity**  
**Purpose**: Assesses AI models for unauthorized modifications, including backdoors and dataset poisoning. Supports trustworthiness and security of model outputs.  
**NIST AI RMF Alignment**: **Map, Measure**  
- **Map**: Understand and identify risks to model/data integrity.  
- **Measure**: Evaluate and mitigate risks through validation techniques.

- **[CVE-Bench — @uiuc-kang-lab](https://github.com/uiuc-kang-lab/cve-bench)** [![GitHub Repo stars](https://img.shields.io/github/stars/uiuc-kang-lab/cve-bench?logo=github&label=&style=social)](https://github.com/uiuc-kang-lab/cve-bench) — How well AI agents can exploit real-world software vulnerabilities that are listed in the CVE database.


#### **Governance & Compliance**  
**Purpose**: Ensures AI security aligns with governance frameworks, industry regulations, and security policies. Supports auditability and risk management.  
**NIST AI RMF Alignment**: **Govern**  
- **Govern**: Establish policies, accountability structures, and compliance controls.  

#### **Privacy & Data Protection**  
**Purpose**: Evaluates AI for risks like data leakage, membership inference, and model inversion. Helps ensure privacy preservation and compliance.  
**NIST AI RMF Alignment**: **Measure, Manage**  
- **Measure**: Identify and assess AI-related privacy risks.  
- **Manage**: Implement security controls to mitigate privacy threats.  

#### **Explainability & Trustworthiness**  
**Purpose**: Assesses AI for transparency, fairness, and bias mitigation. Ensures AI operates in an interpretable and ethical manner.  
**NIST AI RMF Alignment**: **Govern, Map, Measure**  
- **Govern**: Establish policies for fairness, bias mitigation, and transparency.  
- **Map**: Identify potential explainability risks in AI decision-making.  
- **Measure**: Evaluate AI outputs for fairness, bias, and interpretability.  

---
## Incident Response

### Incident Repositories, Trackers & Monitors
- [AI Incident Database (AIID)](https://incidentdatabase.ai/) 
- [MIT AI Risk Repository — Incident Tracker](https://airisk.mit.edu/ai-incident-tracker) 
- [AIAAIC Repository](https://www.aiaaic.org/aiaaic-repository/ai-algorithmic-and-automation-incidents)
- [OECD.AI — AIM: AI Incidents and Hazards Monitor](https://oecd.ai/en/incidents)

### Guides & Playbooks
- [OWASP — GenAI Incident Response Guide](https://genai.owasp.org/resource/genai-incident-response-guide-1-0/) 
- [OWASP — Guide for Preparing & Responding to Deepfake Events](https://genai.owasp.org/resource/guide-for-preparing-and-responding-to-deepfake-events/)

---

## Newsletter
- [Adversarial AI Digest](https://www.linkedin.com/newsletters/adversarial-ai-digest-7298813894498598912/) - A digest of AI security research, threats, governance challenges, and best practices for securing AI systems.

---

## Conferences and Events

- [AI Village @ DEF CON](https://aivillage.org/)
- [AI Summit @ Black Hat](https://www.blackhat.com/)
- [AI Hacking Village @ BSides TLV](https://aihackingvillage.com/)

---

## Reports and Research

### Research Feed

- [AI Security Research Feed](https://research.pwnedby.me/?category=cs.AI&tag=ai) – Continuously updated feed of AI security–related academic papers, preprints, and research indexed from arXiv.
- [AI Security Portal – Literature Database](https://aisecurity-portal.org/en/section/literature-database/) – Categorized database of AI security literature, taxonomy, and related resources.

### Reports
- [CSA — The State of AI and Security Survey Report](https://cloudsecurityalliance.org/artifacts/the-state-of-ai-and-security-survey-report)
- [CSA — Principles to Practice: Responsible AI in a Dynamic Regulatory Environment](https://cloudsecurityalliance.org/artifacts/principles-to-practice-responsible-ai-in-a-dynamic-regulatory-environment)
- [CSA — AI Resilience: A Revolutionary Benchmarking Model for AI Safety](https://cloudsecurityalliance.org/artifacts/ai-resilience-a-revolutionary-benchmarking-model-for-ai-safety) – Governance & compliance benchmarking model.
- [CSA — Using AI for Offensive Security](https://cloudsecurityalliance.org/artifacts/using-ai-for-offensive-security)

📌 *(More to be added – A collection of AI security reports, white papers, and academic studies.)*

---

## Podcasts

- [**The MLSecOps Podcast**](https://podcasts.apple.com/us/podcast/the-mlsecops-podcast/id1679667447) – Insightful conversations with industry leaders and AI experts, exploring the fascinating world of machine learning security operations.

---

## Market Landscape 
*Curated market maps of tools and vendors for securing LLM and agentic AI applications across the lifecycle.*

- **[OWASP — LLM and Generative AI Security Solutions Landscape](https://genai.owasp.org/resource/llm-and-generative-ai-security-solutions-landscape-q12025/)** 
- **[OWASP — AI Security Solutions Landscape for Agentic AI](https://genai.owasp.org/resource/ai-security-solutions-landscape-for-agentic-ai-q3-2025/)** 
- **[Latio — 2025 AI Security Report](https://pulse.latio.tech/p/2025-latio-ai-security-report)** — Market trends and vendor landscape snapshot for AI security.
- **[Woodside Capital Partners — Cybersecurity Sector](https://woodsidecap.com/wcp-cybersecurity-sector-update-state-of-ai-security/)** — A snapshot with vendor breakdowns and landscape view.
- **[Insight Partners — Cybersecurity Portfolio Overview (Market Map)](https://info.insightpartners.com/cybersecurity-portfolio-overview.html?_gl=1*1tyates*_ga*MzcyNjg5MDY1LjE3NTY5MjY4ODc.*_ga_R6M33R23CY*czE3NTY5MjY4ODckbzEkZzEkdDE3NTY5Mjg0NjkkajYwJGwwJGgw)** — Visual market map and portfolio overview across cybersecurity domains.

---

## Startups Blogs
*A curated list of startups securing agentic AI applications, organized by the OWASP Agentic AI lifecycle (Scope & Plan → Govern). Each company appears once in its best-fit stage based on public positioning, and links point to blog/insights for deeper context. Some startups span multiple stages; placements reflect primary focus.*

**Inclusion criteria**
1. Startup has **not been acquired**
2. Has an **active blog**
3. Has an **active GitHub** organization/repository

#### Scope & Plan
*Design-time security: non-human identities, agent threat modeling, privilege boundaries/authn, and memory scoping/isolation.*

> no startups here with active blog and active GitHub account

#### Develop & Experiment
*Secure agent loops and tool use; validate I/O contracts; embed policy hooks; test resilience during co-engineering.*

> no startups here with active blog and active GitHub account

#### Augment & Fine-Tune Data
*Sanitize/trace data and reasoning; validate alignment; protect sensitive memory with privacy controls before deployment.*
- [Skyflow](https://www.skyflow.com/blog) [![GitHub followers](https://img.shields.io/github/followers/skyflowapi?style=social)](https://github.com/skyflowapi)


#### Test & Evaluate
*Adversarial testing for goal drift, prompt injection, and tool misuse; red-team sims; sandboxed calls; decision validation.*
- [Citadel AI](https://citadel-ai.com/blog/) [![GitHub followers](https://img.shields.io/github/followers/citadel-ai?style=social)](https://github.com/citadel-ai)
- [Mindgard](https://www.mindgard.ai/blog) [![GitHub followers](https://img.shields.io/github/followers/Mindgard?style=social)](https://github.com/Mindgard)
- [Troj.ai](https://www.troj.ai/blog) [![GitHub followers](https://img.shields.io/github/followers/trojai?style=social)](https://github.com/trojai)
- [SPLX AI](https://splx.ai/blog) [![GitHub followers](https://img.shields.io/github/followers/splx-ai?style=social)](https://github.com/splx-ai)
- [Octomind](https://octomind.dev/blog) [![GitHub followers](https://img.shields.io/github/followers/OctoMind-dev?style=social)](https://github.com/OctoMind-dev)
- [Patronus AI](https://www.patronus.ai/blog) [![GitHub followers](https://img.shields.io/github/followers/patronus-ai?style=social)](https://github.com/patronus-ai)


#### Release
*Sign models/plugins/memory; verify SBOMs; enforce cryptographically validated policies; register agents/capabilities.*

> no startups here with active blog and active GitHub account

#### Deploy
*Zero-trust activation: rotate ephemeral creds, apply allowlists/LLM firewalls, and fine-grained least-privilege authorization.*
- [Pomerium](https://www.pomerium.com/blog) [![GitHub followers](https://img.shields.io/github/followers/pomerium?style=social)](https://github.com/pomerium)


#### Operate
*Monitor memory mutations for drift/poisoning, detect abnormal loops/misuse, enforce HITL overrides, and scan plugins—continuous, real-time vigilance for resilient operations as systems scale and self-orchestrate.*
- [Lakera](https://www.lakera.ai/blog) [![GitHub followers](https://img.shields.io/github/followers/lakeraai?style=social)](https://github.com/lakeraai)
- [Lasso Security](https://www.lasso.security/blog) [![GitHub followers](https://img.shields.io/github/followers/lasso-security?style=social)](https://github.com/lasso-security)

#### Monitor
*Correlate agent steps/tools/comms; detect anomalies (e.g., goal reversal); keep immutable logs for auditability.*
- [Fiddler](https://www.fiddler.ai/blog) [![GitHub followers](https://img.shields.io/github/followers/fiddler-labs?style=social)](https://github.com/fiddler-labs)
- [Pangea](https://pangea.cloud/blog/) [![GitHub followers](https://img.shields.io/github/followers/pangeacyber?style=social)](https://github.com/pangeacyber)

#### Govern
*Enforce role/task policies, version/retire agents, prevent privilege creep, and align evidence with AI regulations.*
- [GuardionAI](https://guardion.ai/blog) [![GitHub followers](https://img.shields.io/github/followers/GuardionAI?style=social)](https://github.com/GuardionAI)
- [Zenity](https://zenity.io/blog) [![GitHub followers](https://img.shields.io/github/followers/zenitysec?style=social)](https://github.com/zenitysec)

---

## Related Awesome Lists

- [Awesome LLMSecOps — wearetyomsmnv](https://github.com/wearetyomsmnv/Awesome-LLMSecOps) [![GitHub Repo stars](https://img.shields.io/github/stars/wearetyomsmnv/Awesome-LLMSecOps?logo=github&label=&style=social)](https://github.com/wearetyomsmnv/Awesome-LLMSecOps)
- [OSS LLM Security — kaplanlior](https://github.com/kaplanlior/oss-llm-security) [![GitHub Repo stars](https://img.shields.io/github/stars/kaplanlior/oss-llm-security?logo=github&label=&style=social)](https://github.com/kaplanlior/oss-llm-security)
- [Awesome LLM Security — corca-ai](https://github.com/corca-ai/awesome-llm-security) [![GitHub Repo stars](https://img.shields.io/github/stars/corca-ai/awesome-llm-security?logo=github&label=&style=social)](https://github.com/corca-ai/awesome-llm-security)
- [Security for AI — zmre](https://github.com/zmre/awesome-security-for-ai) [![GitHub Repo stars](https://img.shields.io/github/stars/zmre/awesome-security-for-ai?logo=github&label=&style=social)](https://github.com/zmre/awesome-security-for-ai)
- [Awesome AI Security — DeepSpaceHarbor](https://github.com/DeepSpaceHarbor/Awesome-AI-Security) [![GitHub Repo stars](https://img.shields.io/github/stars/DeepSpaceHarbor/Awesome-AI-Security?logo=github&label=&style=social)](https://github.com/DeepSpaceHarbor/Awesome-AI-Security)
- [Awesome AI for Cybersecurity — Billy1900](https://github.com/Billy1900/Awesome-AI-for-cybersecurity) [![GitHub Repo stars](https://img.shields.io/github/stars/Billy1900/Awesome-AI-for-cybersecurity?logo=github&label=&style=social)](https://github.com/Billy1900/Awesome-AI-for-cybersecurity)
- [Awesome ML Security — Trail of Bits](https://github.com/trailofbits/awesome-ml-security) [![GitHub Repo stars](https://img.shields.io/github/stars/trailofbits/awesome-ml-security?logo=github&label=&style=social)](https://github.com/trailofbits/awesome-ml-security)
- [Awesome MLSecOps — RiccardoBiosas](https://github.com/RiccardoBiosas/awesome-MLSecOps) [![GitHub Repo stars](https://img.shields.io/github/stars/RiccardoBiosas/awesome-MLSecOps?logo=github&label=&style=social)](https://github.com/RiccardoBiosas/awesome-MLSecOps)
- [MLSecOps References — disesdi](https://github.com/disesdi/mlsecops_references) [![GitHub Repo stars](https://img.shields.io/github/stars/disesdi/mlsecops_references?logo=github&label=&style=social)](https://github.com/disesdi/mlsecops_references)
- [Awesome ML Privacy Attacks — StratosphereIPS](https://github.com/stratosphereips/awesome-ml-privacy-attacks) [![GitHub Repo stars](https://img.shields.io/github/stars/stratosphereips/awesome-ml-privacy-attacks?logo=github&label=&style=social)](https://github.com/stratosphereips/awesome-ml-privacy-attacks)
- [Awesome LLM Supply Chain Security — ShenaoW](https://github.com/ShenaoW/awesome-llm-supply-chain-security) [![GitHub Repo stars](https://img.shields.io/github/stars/ShenaoW/awesome-llm-supply-chain-security?logo=github&label=&style=social)](https://github.com/ShenaoW/awesome-llm-supply-chain-security)
- [Awesome Prompt Injection — FonduAI](https://github.com/FonduAI/awesome-prompt-injection) [![GitHub Repo stars](https://img.shields.io/github/stars/FonduAI/awesome-prompt-injection?logo=github&label=&style=social)](https://github.com/FonduAI/awesome-prompt-injection)
- [Awesome Jailbreak on LLMs — yueliu1999](https://github.com/yueliu1999/Awesome-Jailbreak-on-LLMs) [![GitHub Repo stars](https://img.shields.io/github/stars/yueliu1999/Awesome-Jailbreak-on-LLMs?logo=github&label=&style=social)](https://github.com/yueliu1999/Awesome-Jailbreak-on-LLMs)
- [Awesome LM-SSP (Large Model Security, Safety & Privacy) — ThuCCSLab](https://github.com/ThuCCSLab/Awesome-LM-SSP) [![GitHub Repo stars](https://img.shields.io/github/stars/ThuCCSLab/Awesome-LM-SSP?logo=github&label=&style=social)](https://github.com/ThuCCSLab/Awesome-LM-SSP)
- [Security & Privacy for LLMs (llm-sp) — chawins](https://github.com/chawins/llm-sp) [![GitHub Repo stars](https://img.shields.io/github/stars/chawins/llm-sp?logo=github&label=&style=social)](https://github.com/chawins/llm-sp)
- [Awesome LVLM Attack — liudaizong](https://github.com/liudaizong/Awesome-LVLM-Attack) [![GitHub Repo stars](https://img.shields.io/github/stars/liudaizong/Awesome-LVLM-Attack?logo=github&label=&style=social)](https://github.com/liudaizong/Awesome-LVLM-Attack)
- [Awesome ML/SP Papers — gnipping](https://github.com/gnipping/Awesome-ML-SP-Papers) [![GitHub Repo stars](https://img.shields.io/github/stars/gnipping/Awesome-ML-SP-Papers?logo=github&label=&style=social)](https://github.com/gnipping/Awesome-ML-SP-Papers)
- [Awesome LLM JailBreak Papers — WhileBug](https://github.com/WhileBug/AwesomeLLMJailBreakPapers) [![GitHub Repo stars](https://img.shields.io/github/stars/WhileBug/AwesomeLLMJailBreakPapers?logo=github&label=&style=social)](https://github.com/WhileBug/AwesomeLLMJailBreakPapers)
- [Awesome Adversarial Machine Learning — man3kin3ko](https://github.com/man3kin3ko/awesome-adversarial-machine-learning) [![GitHub Repo stars](https://img.shields.io/github/stars/man3kin3ko/awesome-adversarial-machine-learning?logo=github&label=&style=social)](https://github.com/man3kin3ko/awesome-adversarial-machine-learning)
- [LLM Security & Privacy — briland](https://github.com/briland/LLM-security-and-privacy) [![GitHub Repo stars](https://img.shields.io/github/stars/briland/LLM-security-and-privacy?logo=github&label=&style=social)](https://github.com/briland/LLM-security-and-privacy)
- [Awesome GenAI Security — jassics](https://github.com/jassics/awesome-genai-security) [![GitHub Repo stars](https://img.shields.io/github/stars/jassics/awesome-genai-security?logo=github&label=&style=social)](https://github.com/jassics/awesome-genai-security)
- [Awesome GenAI CyberHub — Ashfaaq98](https://github.com/Ashfaaq98/awesome-genai-cyberhub) [![GitHub Repo stars](https://img.shields.io/github/stars/Ashfaaq98/awesome-genai-cyberhub?logo=github&label=&style=social)](https://github.com/Ashfaaq98/awesome-genai-cyberhub)
- [Awesome AI for Security — AmanPriyanshu](https://github.com/AmanPriyanshu/Awesome-AI-For-Security) [![GitHub Repo stars](https://img.shields.io/github/stars/AmanPriyanshu/Awesome-AI-For-Security?logo=github&label=&style=social)](https://github.com/AmanPriyanshu/Awesome-AI-For-Security)
- [Awesome ML for Cybersecurity — jivoi](https://github.com/jivoi/awesome-ml-for-cybersecurity) [![GitHub Repo stars](https://img.shields.io/github/stars/jivoi/awesome-ml-for-cybersecurity?logo=github&label=&style=social)](https://github.com/jivoi/awesome-ml-for-cybersecurity)
- [Awesome AI Security — ottosulin](https://github.com/ottosulin/awesome-ai-security) [![GitHub Repo stars](https://img.shields.io/github/stars/ottosulin/awesome-ai-security?logo=github&label=&style=social)](https://github.com/ottosulin/awesome-ai-security)
- [Awesome AI4DevSecOps — awsm-research](https://github.com/awsm-research/Awesome-AI4DevSecOps) [![GitHub Repo stars](https://img.shields.io/github/stars/awsm-research/Awesome-AI4DevSecOps?logo=github&label=&style=social)](https://github.com/awsm-research/Awesome-AI4DevSecOps)
- [Prompt Hacking Resources — PromptLabs](https://github.com/PromptLabs/Prompt-Hacking-Resources) [![GitHub Repo stars](https://img.shields.io/github/stars/PromptLabs/Prompt-Hacking-Resources?logo=github&label=&style=social)](https://github.com/PromptLabs/Prompt-Hacking-Resources)
- [Awesome LALMs Jailbreak — WangCheng0116](https://github.com/WangCheng0116/Awesome-LALMs-Jailbreak) [![GitHub Repo stars](https://img.shields.io/github/stars/WangCheng0116/Awesome-LALMs-Jailbreak?logo=github&label=&style=social)](https://github.com/WangCheng0116/Awesome-LALMs-Jailbreak)
- [Awesome LRMs Safety — WangCheng0116](https://github.com/WangCheng0116/Awesome-LRMs-Safety) [![GitHub Repo stars](https://img.shields.io/github/stars/WangCheng0116/Awesome-LRMs-Safety?logo=github&label=&style=social)](https://github.com/WangCheng0116/Awesome-LRMs-Safety)
- [Awesome LLM Safety — ydyjya](https://github.com/ydyjya/Awesome-LLM-Safety) [![GitHub Repo stars](https://img.shields.io/github/stars/ydyjya/Awesome-LLM-Safety?logo=github&label=&style=social)](https://github.com/ydyjya/Awesome-LLM-Safety)
- [Awesome MCP Security — Puliczek](https://github.com/Puliczek/awesome-mcp-security) [![GitHub Repo stars](https://img.shields.io/github/stars/Puliczek/awesome-mcp-security?logo=github&label=&style=social)](https://github.com/Puliczek/awesome-mcp-security)

---

## Common Acronyms

| Acronym  | Full Form                                                                 |
|:---------|:--------------------------------------------------------------------------|
| AI       | Artificial Intelligence                                                   |
| AGI      | Artificial General Intelligence                                           |
| ALBERT   | A Lite BERT                                                               |
| BERT     | Bidirectional Encoder Representations from Transformers                   |
| BGMAttack| Black-box Generative Model-based Attack                                   |
| CBA      | Composite Backdoor Attack                                                 |
| CCPA     | California Consumer Privacy Act                                           |
| DAN      | Do Anything Now                                                           |
| DNN      | Deep Neural Network                                                       |
| DP       | Differential Privacy                                                      |
| FL       | Federated Learning                                                        |
| GDPR     | General Data Protection Regulation                                        |
| GA       | Genetic Algorithm                                                         |
| GPT      | Generative Pre-trained Transformer                                        |
| HIPAA    | Health Insurance Portability and Accountability Act                       |
| LM       | Language Model                                                            |
| LLM      | Large Language Model                                                      |
| Llama    | Large Language Model Meta AI                                              |
| MIA      | Membership Inference Attack                                               |
| MDP      | Masking-Differential Prompting                                            |
| MLM      | Masked Language Model                                                     |
| NLP      | Natural Language Processing                                               |
| OOD      | Out Of Distribution                                                       |
| PI       | Prompt Injection                                                          |
| PII      | Personally Identifiable Information                                       |
| PAIR     | Prompt Automatic Iterative Refinement                                     |
| PLM      | pre-trained Language Model                                                |
| RL       | Reinforcement Learning                                                    |
| RLHF     | Reinforcement Learning from Human Feedback                                |
| RoBERTa  | Robustly optimized BERT approach                                          |
| SGD      | Stochastic Gradient Descent                                               |
| TAG      | Gradient Attack on Transformer-based Language Models                      |
| XLNet    | Transformer-XL with autoregressive and autoencoding pre-training          |


---

## Contributing

Contributions are welcome! If you have new resources, tools, or insights to add, feel free to submit a pull request.

This repository follows the **[Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)** guidelines.

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](LICENSE)

© 2025 Tal Eliyahu. Licensed under the **MIT License**. See [`LICENSE`](LICENSE).

