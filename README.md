# Awesome AI Security

Curated resources, research, and tools for securing AI systems.

[![Status: Work in Progress](https://img.shields.io/badge/status-work--in--progress-red)](#) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Join AISecHub on LinkedIn](https://img.shields.io/badge/Join-AISecHub%20on%20LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/groups/14545517/)
[![Follow @AISecHub on X](https://img.shields.io/badge/Follow-@AISecHub-black?logo=x&logoColor=white)](https://x.com/AISecHub)
[![Join @AISecHub on Telegram](https://img.shields.io/badge/Join-@AISecHub-2CA5E0?logo=telegram&logoColor=white)](https://t.me/AISecHub)
---

## Contents

- [Best Practices and Security Standards](#best-practices-and-security-standards)
- [Tools](#tools)
- [Attack & Defense Matrices](#attack--defense-matrices)
- [Checklists](#checklists)
- [Risk and Incident Databases](#ai-risk-and-incident-databases)
- [Glossary](#glossary)
- [Taxonomy](#taxonomy)
- [Knowledge Bases](#ai-security-knowledge-bases)
- [Datasets](#datasets)
- [Courses](#ai-security-courses)
- [Guides & Learning Resources](#ai-security-guides--learning-resources)
- [Research Working Groups](#research-working-groups)
- [Communities & Social Groups](#communities--social-groups)
- [Benchmarking Categories](#benchmarking-categories)
- [Incident Response](#incident-response)
- [Supply Chain Security](#supply-chain-security)
- [Newsletter](#newsletter)
- [Conferences and Events](#conferences-and-events)
- [Reports and Research](#reports-and-research)
- [CTFs & Challenges](#ctf-challenges)
- [Podcasts](#podcasts)
- [Solutions Landscape](#solutions-landscape)
- [Related Awesome Lists](#related-awesome-lists)

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


### Standards & Risk Lists
- [OWASP — Top 10 for Large Language Model Applications](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-top-10-for-large-language-model-applications?logo=github&label=&style=social)](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications)
- [OWASP — LLM Security Verification Standard (LLMSVS)](https://github.com/OWASP/www-project-llm-verification-standard) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-llm-verification-standard?logo=github&label=&style=social)](https://github.com/OWASP/www-project-llm-verification-standard)
- [OWASP — Artificial Intelligence Security Verification Standard (AISVS)](https://github.com/OWASP/AISVS) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/AISVS?logo=github&label=&style=social)](https://github.com/OWASP/AISVS)
- [OWASP — Artificial Intelligence Vulnerability Scoring System](https://github.com/OWASP/www-project-artificial-intelligence-vulnerability-scoring-system) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-artificial-intelligence-vulnerability-scoring-system?logo=github&label=&style=social)](https://github.com/OWASP/www-project-artificial-intelligence-vulnerability-scoring-system)
- [CSA — AI Controls Matrix (AICM)](https://cloudsecurityalliance.org/artifacts/ai-controls-matrix)


### Testing, Red Teaming & Incident Response
- [OWASP — AI Testing Guide](https://github.com/OWASP/www-project-ai-testing-guide) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-ai-testing-guide?logo=github&label=&style=social)](https://github.com/OWASP/www-project-ai-testing-guide)
- [OWASP — Red Teaming Guide](https://genai.owasp.org/resource/genai-red-teaming-guide/)
- [OWASP — Incident Response Guide](https://genai.owasp.org/resource/genai-incident-response-guide-1-0/)
- [OWASP — LLM Exploit Generation](https://genai.owasp.org/resource/owasp-llm-exploit-generation-v1-0-pdf/)
- [CSA — Agentic AI Red Teaming Guide](https://cloudsecurityalliance.org/artifacts/agentic-ai-red-teaming-guide)


### Guidance & Best Practices
- [OWASP — AI Security and Privacy Guide](https://github.com/OWASP/www-project-ai-security-and-privacy-guide) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-ai-security-and-privacy-guide?logo=github&label=&style=social)](https://github.com/OWASP/www-project-ai-security-and-privacy-guide)
- [OWASP — LLM and Generative AI Security Solutions Landscape](https://genai.owasp.org/resource/llm-and-generative-ai-security-solutions-landscape-q12025/)
- [OWASP — LLM and Gen AI Data Security Best Practices](https://genai.owasp.org/resource/llm-and-gen-ai-data-security-best-practices/)
- [OWASP — GenAI Security Project](https://github.com/OWASP/genai-security-project) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/genai-security-project?logo=github&label=&style=social)](https://github.com/OWASP/genai-security-project)
- [CSA — Secure LLM Systems: Essential Authorization Practices](https://cloudsecurityalliance.org/artifacts/securing-llm-backed-systems-essential-authorization-practices)
- [NIST — Four Principles of Explainable Artificial Intelligence](https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=933399)
- [OASIS CoSAI — Preparing Defenders of AI Systems](https://github.com/cosai-oasis/ws2-defenders/blob/main/preparing-defenders-of-ai-systems.md) [![GitHub Repo stars](https://img.shields.io/github/stars/cosai-oasis/ws2-defenders?logo=github&label=&style=social)](https://github.com/cosai-oasis/ws2-defenders)
- [CISA — AI Data Security: Best Practices for Securing Data Used to Train & Operate AI Systems](https://www.cisa.gov/news-events/alerts/2025/05/22/new-best-practices-guide-securing-ai-data-released)
  

### Agentic AI Security & Governance
- [OWASP — Agent Observability Standard (AOS)](https://github.com/OWASP/www-project-agent-observability-standard) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-agent-observability-standard?logo=github&label=&style=social)](https://github.com/OWASP/www-project-agent-observability-standard)
- [OWASP — Agent Name Service (ANS) for Secure AI Agent Discovery](https://genai.owasp.org/resource/agent-name-service-ans-for-secure-al-agent-discovery-v1-0/)
- [OWASP — Agentic AI - Threats and Mitigations](https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/)
- [OWASP — Securing Agentic Applications Guide](https://genai.owasp.org/resource/securing-agentic-applications-guide-1-0/)
- [OWASP — Multi-Agentic System Threat Modeling Guide](https://genai.owasp.org/resource/multi-agentic-system-threat-modeling-guide-v1-0/)
- [OWASP — State of Agentic AI Security and Governance](https://genai.owasp.org/resource/state-of-agentic-ai-security-and-governance-1-0/)
- [CSA — Secure Agentic System Design: A Trait-Based Approach](https://cloudsecurityalliance.org/artifacts/secure-agentic-system-design)

---

## Tools

### Active LLM Vulnerability Scanners
*(Tools that actively probe LLMs to uncover vulnerabilities)*

- **Fuzzers** – Generate/mutate inputs to trigger unsafe or undesired model behaviors (e.g., jailbreaks, injections).
  - **[LLMFuzzer](https://github.com/mnns/LLMFuzzer)** [![GitHub Repo stars](https://img.shields.io/github/stars/mnns/LLMFuzzer?logo=github&label=&style=social)](https://github.com/mnns/LLMFuzzer)
  - **[FuzzyAI](https://github.com/cyberark/FuzzyAI)** [![GitHub Repo stars](https://img.shields.io/github/stars/cyberark/FuzzyAI?logo=github&label=&style=social)](https://github.com/cyberark/FuzzyAI)
  - **[GPTFuzz](https://github.com/sherdencooper/GPTFuzz)** [![GitHub Repo stars](https://img.shields.io/github/stars/sherdencooper/GPTFuzz?logo=github&label=&style=social)](https://github.com/sherdencooper/GPTFuzz)

- **Prompt Injection Scanners** – Detect known prompt injection patterns and payloads.
  - **[Promptmap](https://github.com/utkusen/promptmap)** [![GitHub Repo stars](https://img.shields.io/github/stars/utkusen/promptmap?logo=github&label=&style=social)](https://github.com/utkusen/promptmap)

- **Comprehensive Security Testers** – Multi-module scanners for multiple vulnerability classes in one run (injection, leakage, jailbreak, unsafe output).
  - **[Garak](https://github.com/NVIDIA/garak)** [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/garak?logo=github&label=&style=social)](https://github.com/NVIDIA/garak)
  - **[Agentic Security](https://github.com/msoedov/agentic_security)** [![GitHub Repo stars](https://img.shields.io/github/stars/msoedov/agentic_security?logo=github&label=&style=social)](https://github.com/msoedov/agentic_security)

### Automated Red-Teaming Harnesses
*(Goal-driven automated red-team frameworks for LLM/agent apps; run multi-step attacks and can be paired with scanners (e.g., garak) in CI.)*

- **[PyRIT](https://github.com/Azure/PyRIT)** [![GitHub Repo stars](https://img.shields.io/github/stars/Azure/PyRIT?logo=github&label=&style=social)](https://github.com/Azure/PyRIT)
- **[DeepTeam](https://github.com/confident-ai/deepteam)** [![GitHub Repo stars](https://img.shields.io/github/stars/confident-ai/deepteam?logo=github&label=&style=social)](https://github.com/confident-ai/deepteam)
- **[promptfoo](https://github.com/promptfoo/promptfoo)** [![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?logo=github&label=&style=social)](https://github.com/promptfoo/promptfoo)

### Code Security Review

- **[claude-code-security-review - Anthropics](https://github.com/anthropics/claude-code-security-review)** [![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/claude-code-security-review?logo=github&label=&style=social)](https://github.com/anthropics/claude-code-security-review) — An AI-powered security review GitHub Action using Claude to analyze code changes for security vulnerabilities.
  
### Benchmarks / Test Suites
*(Standardized datasets and scoring methods for resilience measurement.)*
- **[Purple Llama — CyberSecEval](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama)
- **[AgentDojo](https://github.com/ethz-spylab/agentdojo)** [![GitHub Repo stars](https://img.shields.io/github/stars/ethz-spylab/agentdojo?logo=github&label=&style=social)](https://github.com/ethz-spylab/agentdojo)
- **[JailbreakBench](https://github.com/JailbreakBench/jailbreakbench)** [![GitHub Repo stars](https://img.shields.io/github/stars/JailbreakBench/jailbreakbench?logo=github&label=&style=social)](https://github.com/JailbreakBench/jailbreakbench)

### Data Security & Integrity — Model Artifact Scanning (static)
*Scan model files before loading to catch unsafe deserialization (e.g., pickle RCE) and improve supply-chain hygiene.*

- **[Protect AI — ModelScan](https://github.com/protectai/modelscan)** [![GitHub Repo stars](https://img.shields.io/github/stars/protectai/modelscan?logo=github&label=&style=social)](https://github.com/protectai/modelscan)
- **[Trail of Bits — Fickling](https://github.com/trailofbits/fickling)** [![GitHub Repo stars](https://img.shields.io/github/stars/trailofbits/fickling?logo=github&label=&style=social)](https://github.com/trailofbits/fickling)
- **[picklescan](https://github.com/mmaitre314/picklescan)** [![GitHub Repo stars](https://img.shields.io/github/stars/mmaitre314/picklescan?logo=github&label=&style=social)](https://github.com/mmaitre314/picklescan)

### Model Training & Hardening (white-box/robustness)
*Attack/defense libraries for robustness research and training-time hardening.*

- **[Foolbox](https://github.com/bethgelab/foolbox)** [![GitHub Repo stars](https://img.shields.io/github/stars/bethgelab/foolbox?logo=github&label=&style=social)](https://github.com/bethgelab/foolbox)

### Model Evaluation & Adversarial Testing (white-box & general eval)
*Evaluate/defend against evasion, poisoning, extraction, inference attacks.*

- **[Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)** [![GitHub Repo stars](https://img.shields.io/github/stars/Trusted-AI/adversarial-robustness-toolbox?logo=github&label=&style=social)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)
- **[TextAttack](https://github.com/QData/TextAttack)** [![GitHub Repo stars](https://img.shields.io/github/stars/QData/TextAttack?logo=github&label=&style=social)](https://github.com/QData/TextAttack)
- **[Giskard](https://github.com/Giskard-AI/giskard)** [![GitHub Repo stars](https://img.shields.io/github/stars/Giskard-AI/giskard?logo=github&label=&style=social)](https://github.com/Giskard-AI/giskard)

### Runtime Guardrails & Policy Enforcement
*Filters/classifiers used inline at runtime to block jailbreaks, prompt injection, and leaks.*

- **[NeMo Guardrails (NVIDIA)](https://github.com/NVIDIA/NeMo-Guardrails)** [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails?logo=github&label=&style=social)](https://github.com/NVIDIA/NeMo-Guardrails)
- **[Rebuff (Protect AI)](https://github.com/protectai/rebuff)** [![GitHub Repo stars](https://img.shields.io/github/stars/protectai/rebuff?logo=github&label=&style=social)](https://github.com/protectai/rebuff)
- **[LLM Guard (Protect AI)](https://github.com/protectai/llm-guard)** [![GitHub Repo stars](https://img.shields.io/github/stars/protectai/llm-guard?logo=github&label=&style=social)](https://github.com/protectai/llm-guard)
- **[Llama Guard (Meta)](https://github.com/meta-llama/PurpleLlama/tree/main/Llama-Guard4)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama) [Model card](https://huggingface.co/meta-llama/Llama-Guard-4-12B)
- **[LlamaFirewall (Meta)](https://github.com/meta-llama/PurpleLlama/tree/main/LlamaFirewall)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama)
- **[Code Shield (Meta)](https://github.com/meta-llama/PurpleLlama/tree/main/CodeShield)** [![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/PurpleLlama?logo=github&label=&style=social)](https://github.com/meta-llama/PurpleLlama)

### MCP Security, Gateways & Testing
*Secure, test, and operate Model Context Protocol (MCP) servers/clients.*

- **[MCP Inspector](https://github.com/modelcontextprotocol/inspector)** [![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector?logo=github&label=&style=social)](https://github.com/modelcontextprotocol/inspector)
- **[mcp-scan (Invariant Labs)](https://github.com/invariantlabs-ai/mcp-scan)** [![GitHub Repo stars](https://img.shields.io/github/stars/invariantlabs-ai/mcp-scan?logo=github&label=&style=social)](https://github.com/invariantlabs-ai/mcp-scan)
- **[MCP Shield — riseandignite](https://github.com/riseandignite/mcp-shield)** [![GitHub Repo stars](https://img.shields.io/github/stars/riseandignite/mcp-shield?logo=github&label=&style=social)](https://github.com/riseandignite/mcp-shield)

### Pentesting Assistants
*Designed for security engineers, pentesters, and bounty hunters—tools to speed recon, triage, and testing.*

- **[PentestGPT](https://github.com/GreyDGL/PentestGPT)** [![GitHub Repo stars](https://img.shields.io/github/stars/GreyDGL/PentestGPT?logo=github&label=&style=social)](https://github.com/GreyDGL/PentestGPT)
- **[CAI — Cybersecurity AI](https://github.com/aliasrobotics/cai)** [![GitHub Repo stars](https://img.shields.io/github/stars/aliasrobotics/cai?logo=github&label=&style=social)](https://github.com/aliasrobotics/cai) 
- **[hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT)** [![GitHub Repo stars](https://img.shields.io/github/stars/ipa-lab/hackingBuddyGPT?logo=github&label=&style=social)](https://github.com/ipa-lab/hackingBuddyGPT)
- **[HexStrike AI](https://github.com/0x4m4/hexstrike-ai)** [![GitHub Repo stars](https://img.shields.io/github/stars/0x4m4/hexstrike-ai?logo=github&label=&style=social)](https://github.com/0x4m4/hexstrike-ai)
- **[PortSwigger — MCP Server](https://github.com/PortSwigger/mcp-server)** [![GitHub Repo stars](https://img.shields.io/github/stars/PortSwigger/mcp-server?logo=github&label=&style=social)](https://github.com/PortSwigger/mcp-server)
- **[BurpGPT](https://github.com/aress31/burpgpt)** [![GitHub Repo stars](https://img.shields.io/github/stars/aress31/burpgpt?logo=github&label=&style=social)](https://github.com/aress31/burpgpt)
- **[Nebula](https://github.com/berylliumsec/nebula)** [![GitHub Repo stars](https://img.shields.io/github/stars/berylliumsec/nebula?logo=github&label=&style=social)](https://github.com/berylliumsec/nebula)
---

## Attack & Defense Matrices
*Matrix-style resources covering adversarial TTPs and curated defensive techniques for AI systems.*

### Attack
- [MITRE ATLAS](https://atlas.mitre.org) – Adversarial TTP matrix and knowledge base for threats to AI systems.
- [GenAI Attacks Matrix](https://ttps.ai/matrix.html#genai-attacks-matrix) – Matrix of TTPs targeting GenAI apps, copilots, and agents.

### Defense
- [AIDEFEND — AI Defense Framework](https://github.com/edward-playground/aidefense-framework) [![GitHub Repo stars](https://img.shields.io/github/stars/edward-playground/aidefense-framework?logo=github&label=&style=social)](https://github.com/edward-playground/aidefense-framework) — Interactive defensive countermeasures knowledge base with Tactics / Pillars / Phases views; maps mitigations to MITRE ATLAS, MAESTRO, and OWASP LLM risks. • **Live demo:** https://edward-playground.github.io/aidefense-framework/

---

## Checklists

- [OWASP — LLM Applications Cybersecurity & Governance Checklist](https://genai.owasp.org/resource/llm-applications-cybersecurity-and-governance-checklist-english/)
- [SlowMist — MCP Security Checklist](https://github.com/slowmist/MCP-Security-Checklist) [![GitHub Repo stars](https://img.shields.io/github/stars/slowmist/MCP-Security-Checklist?logo=github&label=&style=social)](https://github.com/slowmist/MCP-Security-Checklist)

---

## AI Risk and Incident Databases

- [MIT AI Risk Repository](https://airisk.mit.edu/)
- [AI Incident Database (AIID)](https://incidentdatabase.ai/)

---

## Supply Chain Security

Guidance and standards for securing the AI/ML software supply chain (models, datasets, code, and pipelines). *No tools here—just specs and frameworks.*

- [OWASP — AI Bill of Materials (AIBOM)](https://github.com/OWASP/www-project-aibom) [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/www-project-aibom?logo=github&label=&style=social)](https://github.com/OWASP/www-project-aibom)
- [NIST — Secure Software Development Practices for Generative AI and Dual-Use Foundation Models: An SSDF Community Profile (SP 800-218A)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218A.pdf)

---

## Glossary

- [NIST - "The Language of Trustworthy AI: An In-Depth Glossary of Terms"](https://airc.nist.gov/glossary/)

---

## Taxonomy

- [ARC PI Taxonomy](https://github.com/Arcanum-Sec/arc_pi_taxonomy)
- [CSA — Large Language Model (LLM) Threats Taxonomy](https://cloudsecurityalliance.org/artifacts/csa-large-language-model-llm-threats-taxonomy)


---

## AI Security Knowledge Bases

- [AI Security Portal – Literature Database](https://aisecurity-portal.org/en/section/literature-database/) – Categorized database of AI security literature, taxonomy, and related resources.

---

## Datasets

### Cybersecurity Skills (CTFs & Hands-On Labs)
Interactive CTFs and self-contained labs for hands-on security skills (web, pwn, crypto, forensics, reversing). **Used to** assess practical reasoning, tool use, and end-to-end task execution.

- **[NYU CTF Bench](https://github.com/NYU-LLM-CTF/LLM_CTF_Database)** [![GitHub Repo stars](https://img.shields.io/github/stars/NYU-LLM-CTF/LLM_CTF_Database?logo=github&label=&style=social)](https://github.com/NYU-LLM-CTF/LLM_CTF_Database)

### Cybersecurity Knowledge (Q&A)
Structured Q&A datasets assessing security knowledge and terminology. **Used to** evaluate factual recall and conceptual understanding.

- **[CyberMetric](https://github.com/CyberMetric)** [![GitHub Repo stars](https://img.shields.io/github/stars/CyberMetric?logo=github&label=&style=social)](https://github.com/CyberMetric)
 
### Secure Coding & Vulnerability Detection
Code snippet datasets labeled as vulnerable or secure, often tied to CWEs (Common Weakness Enumeration). **Used to** evaluate the model’s ability to recognize insecure code patterns and suggest secure fixes.

- **[LLMSecEval](https://github.com/tuhh-softsec/LLMSecEval)** [![GitHub Repo stars](https://img.shields.io/github/stars/tuhh-softsec/LLMSecEval?logo=github&label=&style=social)](https://github.com/tuhh-softsec/LLMSecEval)

### Jailbreak & Guardrail Evaluation
Adversarial prompt datasets—both text-only and multimodal—designed to bypass safety mechanisms or test refusal logic.
**Used to** test how effectively a model resists jailbreaks and enforces policy-based refusal.

- **[CySecBench (Prompt Dataset)](https://github.com/cysecbench/dataset)** — 12,662 cybersecurity-themed jailbreak/adversarial prompts.
- **[JailBreakV-28K (Hugging Face)](https://huggingface.co/datasets/JailBreakV-28K)** — 28K multimodal (text + image) jailbreak test cases designed to test alignment vulnerabilities in MLLMs. 
- **[LLM Red-Teaming Prompts](https://huggingface.co/datasets/llm-redteaming-prompts)** — Contains initial assessment prompts, teaching prompts, and successful red-teaming prompts across different harm categories.
- **[Do-Not-Answer](https://github.com/Libr-AI/do-not-answer)** — Prompts that a safe, responsibly-aligned model should refuse to answer.

### Prompt Injection & Malicious Prompt Detection
Datasets labeled with whether prompts are benign or malicious (i.e., injection attempts).
**Used to** evaluate an LLM’s ability to detect and neutralize prompt-injection style attacks.

- **[Prompt Injection Dataset](https://github.com/AhsanAyub/malicious-prompt-detection)** — Classified prompts labeled as malicious or benign for prompt injection detection experiments.
- **[LLMail-Inject Challenge Dataset](https://github.com/microsoft/llmail-inject-challenge)** — Email-based adaptive prompt injection dataset with extensive participation and analysis.

---

## AI Security Courses

- [Microsoft AI Security Learning Path](https://learn.microsoft.com/en-us/training/browse/?filter-roles=ai%20&roles=ai-engineer&subjects=security) – Free training modules on AI security, covering secure AI model development, risk management, and threat mitigation.
- [AWS AI Security Training](https://explore.skillbuilder.aws/learn/external-ecommerce;view=none;redirectURL=?ctldoc-catalog-0=se-%22AI%20Security%22) – Free AWS courses on securing AI applications, risk management, and implementing security best practices in AI/ML environments.

---

## AI Security Guides & Learning Resources

- [Nightfall AI Security 101](https://www.nightfall.ai/ai-security-101) – A centralized learning hub for AI security, offering an evolving library of concepts, emerging risks, and foundational principles in securing AI systems.

### Foundations
- [SANS — AI Cybersecurity Careers](https://www.sans.org/cybersecurity-careers/) — Career pathways poster + training map; helpful baseline skills that transfer to AI security (IR, DFIR, detection, threat hunting).

---

## Research Working Groups

- [Cloud Security Alliance (CSA) AI Security Working Groups](https://cloudsecurityalliance.org/research/working-groups) – Collaborative research groups focused on AI security, cloud security, and emerging threats in AI-driven systems.
- [OWASP Top 10 for LLM & Generative AI Security Risks Project](https://genai.owasp.org/contribute/) – An open-source initiative addressing critical security risks in Large Language Models (LLMs) and Generative AI applications, offering resources and guidelines to mitigate emerging threats.
- [CWE Artificial Intelligence Working Group (AI WG)](https://cwe.mitre.org/community/working_groups.html) – The AI WG was established by CWE™ and CVE® community stakeholders to identify and address gaps in the CWE corpus where AI-related weaknesses are not adequately covered, and work collaboratively to fix them.

📌 *(More working groups to be added.)*

---

## Communities & Social Groups

- [AI Security Hub (LinkedIn Group)](https://www.linkedin.com/groups/14545517/)

---

## Benchmarking Categories

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

### Incident Databases
- [AI Incident Database (AIID)](https://incidentdatabase.ai/) 
- [MIT AI Risk Repository — Incident Tracker](https://airisk.mit.edu/ai-incident-tracker) 
- [AIAAIC Repository](https://www.aiaaic.org/aiaaic-repository/ai-algorithmic-and-automation-incidents)

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

- [AI Security Research Feed](https://research.pwnedby.me/?category=cs.AI&tag=ai) – Continuously updated feed of AI security–related academic papers, preprints, and research indexed from arXiv.
- [CSA — The State of AI and Security Survey Report](https://cloudsecurityalliance.org/artifacts/the-state-of-ai-and-security-survey-report)
- [CSA — Principles to Practice: Responsible AI in a Dynamic Regulatory Environment](https://cloudsecurityalliance.org/artifacts/principles-to-practice-responsible-ai-in-a-dynamic-regulatory-environment)
- [CSA — AI Resilience: A Revolutionary Benchmarking Model for AI Safety](https://cloudsecurityalliance.org/artifacts/ai-resilience-a-revolutionary-benchmarking-model-for-ai-safety) – Governance & compliance benchmarking model.
- [CSA — Using AI for Offensive Security](https://cloudsecurityalliance.org/artifacts/using-ai-for-offensive-security)

📌 *(More to be added – A collection of AI security reports, white papers, and academic studies.)*

---

## CTF Challenges

- [AI GOAT](https://github.com/dhammon/ai-goat) – A set of LLM security challenges focused on identifying and exploiting vulnerabilities in AI systems.
- [Gandalf CTF](https://gandalf.lakera.ai/) – A challenge where participants attempt to extract hidden passphrases from an evolving AI model through prompt engineering techniques.
- [DamnVulnerableLLMApplication-Demo](https://github.com/greshake/DamnVulnerableLLMApp) – A project designed for security researchers to practice LLM hacking techniques and for AI companies to improve the security of their models and systems.

---

## Podcasts

- [**The MLSecOps Podcast**](https://podcasts.apple.com/us/podcast/the-mlsecops-podcast/id1679667447) – Insightful conversations with industry leaders and AI experts, exploring the fascinating world of machine learning security operations.

---

## Solutions Landscape 
*Curated market maps of tools and vendors for securing LLM and agentic AI applications across the lifecycle.*

- [OWASP — LLM and Generative AI Security Solutions Landscape](https://genai.owasp.org/resource/llm-and-generative-ai-security-solutions-landscape-q12025/)
- [OWASP — AI Security Solutions Landscape for Agentic AI](https://genai.owasp.org/resource/ai-security-solutions-landscape-for-agentic-ai-q3-2025/)
- [Latio — 2025 AI Security Report](https://pulse.latio.tech/p/2025-latio-ai-security-report) – Market trends and vendor landscape snapshot for AI security.
- [Woodside Capital Partners — Cybersecurity Sector](https://woodsidecap.com/wcp-cybersecurity-sector-update-state-of-ai-security/) — A snapshot with vendor breakdowns and landscape view.
  
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

## Contributing

Contributions are welcome! If you have new resources, tools, or insights to add, feel free to submit a pull request.

This repository follows the **[Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)** guidelines.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under the **Creative Commons Zero v1.0 Universal** license.
