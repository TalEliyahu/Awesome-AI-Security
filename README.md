# Awesome AI Security 🛡️

> Curated resources, research, and tools for securing AI systems.

This list is still a work in progress — check back in a few days.
[![Status: Work in Progress](https://img.shields.io/badge/status-work--in--progress-red)](#) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## Table of Contents

- [Best Practices and Security Standards](#best-practices-and-security-standards)
- [AI Risk and Incident Databases](#ai-risk-and-incident-databases)
- [Glossary](#glossary)
- [Taxonomy](#taxonomy)
- [AI Security Knowledge Bases](#ai-security-knowledge-bases)
- [Benchmarks](#benchmarks)
- [Datasets](#datasets)
- [AI Security Courses](#ai-security-courses)
- [AI Security Guides & Learning Resources](#ai-security-guides--learning-resources)
- [Research Working Groups](#research-working-groups)
- [Additional AI Security Resources](#additional-ai-security-resources)
- [Newsletter](#newsletter)
- [Conferences and Events](#conferences-and-events)
- [Reports and Research](#reports-and-research)
- [CTF Challenges](#ctf-challenges)
- [Tools](#tools)
- [Podcasts](#podcasts)

---

## Best Practices and Security Standards

- [NIST AI Risk Management Framework (AI RMF)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
- [NIST AI Risk Management Framework Playbook](https://airc.nist.gov/airmf-resources/playbook/)
- [OWASP AI Exchange](https://owaspai.org/docs/ai_security_overview/)
- [OWASP Top 10 for LLM and Generative AI](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [ISO/IEC 42001:2023 – Information technology — Artificial intelligence — Management system](https://www.iso.org/standard/81230.html)

---

## AI Risk and Incident Databases

- [MIT AI Risk Repository](https://airisk.mit.edu/)
- [AI Incident Database (AIID)](https://incidentdatabase.ai/)
- [AI/ML Supply Chain Vulnerability Database](https://sightline.protectai.com/vulnerabilities)

---

## Glossary

- [NIST - "The Language of Trustworthy AI: An In-Depth Glossary of Terms"](https://airc.nist.gov/glossary/)

---

## Taxonomy

- [ARC PI Taxonomy](https://github.com/Arcanum-Sec/arc_pi_taxonomy)

---

## AI Security Knowledge Bases

- [MITRE ATLAS](http://atlas.mitre.org) – A knowledge base of tactics, techniques, and case studies for adversarial threats targeting AI systems.
- [GenAI Attacks Matrix](https://ttps.ai/matrix.html#genai-attacks-matrix) – A structured knowledge base documenting TTPs used to target GenAI-based systems, copilots, and agents.

---

## Benchmarks

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

## Datasets

### Cybersecurity Knowledge & Skills
Structured Q&A datasets and CTF-style challenges that evaluate cybersecurity reasoning and terminology.
**Used to** assess an LLM’s domain knowledge, factual recall, and understanding of security concepts.

- **[CyberMetric](https://github.com/CyberMetric)** — Multiple-choice cybersecurity Q&A dataset (80–10,000 questions).
- **[NYU CTF Bench (LLM_CTF Database)](https://github.com/NYU-LLM-CTF/LLM_CTF_Database)** — Interactive, Dockerized CTF challenges spanning areas like exploitation, cryptography, and forensics.

---

### Secure Coding & Vulnerability Detection
Code snippet datasets labeled as vulnerable or secure, often tied to CWEs (Common Weakness Enumeration).
**Used to** evaluate the model’s ability to recognize insecure code patterns and suggest secure fixes.

- **[LLMSecEval](https://github.com/tuhh-softsec/LLMSecEval)** — Natural language prompts linked to CWE Top 25, with secure vs. vulnerable code context for evaluating LLM code security.

---

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
- [Google's Secure AI Framework (SAIF)](https://saif.google/) – SAIF offers guidance for organizations looking to secure AI systems. Google has created SAIF, including a SAIF Risk Self-Assessment, to support the implementation of SAIF in organizations and help build and deploy AI systems securely.

---

## Research Working Groups

- [Cloud Security Alliance (CSA) AI Security Working Groups](https://cloudsecurityalliance.org/research/working-groups) – Collaborative research groups focused on AI security, cloud security, and emerging threats in AI-driven systems.
- [OWASP Top 10 for LLM & Generative AI Security Risks Project](https://genai.owasp.org/contribute/) – An open-source initiative addressing critical security risks in Large Language Models (LLMs) and Generative AI applications, offering resources and guidelines to mitigate emerging threats.
- [CWE Artificial Intelligence Working Group (AI WG)](https://cwe.mitre.org/community/working_groups.html) – The AI WG was established by CWE™ and CVE® community stakeholders to identify and address gaps in the CWE corpus where AI-related weaknesses are not adequately covered, and work collaboratively to fix them.

📌 *(More working groups to be added.)*

---

## Additional AI Security Resources

- [LLM Security](http://llmsecurity.net)
- [Vinija AI](http://vinija.ai/models/LLM/)

---

## Newsletter

- [Adversarial AI Digest](https://www.linkedin.com/newsletters/adversarial-ai-digest-7298813894498598912/) - A digest of AI security research, threats, governance challenges, and best practices for securing AI systems.
- [AI Cyber Magazine](https://issuu.com/aicybermagazine) – AI Cyber Magazine provides quality in-depth analysis, insightful interviews, thoughtfully curated high-value resources, technical how-to articles, and thought leadership at the intersection of Artificial Intelligence and Cybersecurity.

---

## Conferences and Events

- [AI Village (DEF CON)](https://aivillage.org/)
- [Black Hat AI Summit](https://www.blackhat.com/)

---

## Reports and Research

- [AI Security Research Feed](https://research.pwnedby.me/?category=cs.AI&tag=ai) – Continuously updated feed of AI security–related academic papers, preprints, and research indexed from arXiv.
- [AI Security Portal – Literature Database](https://aisecurity-portal.org/en/section/literature-database/) – Categorized database of AI security literature, taxonomy, and related resources.



📌 *(More to be added – A collection of AI security reports, white papers, and academic studies.)*

---

## CTF Challenges

- [AI GOAT](https://github.com/dhammon/ai-goat) – A set of LLM security challenges focused on identifying and exploiting vulnerabilities in AI systems.
- [Gandalf CTF](https://gandalf.lakera.ai/) – A challenge where participants attempt to extract hidden passphrases from an evolving AI model through prompt engineering techniques.
- [DamnVulnerableLLMApplication-Demo](https://github.com/greshake/DamnVulnerableLLMApp) – A project designed for security researchers to practice LLM hacking techniques and for AI companies to improve the security of their models and systems.

---

## Tools

### Active LLM Vulnerability Scanners
*(Tools that actively probe LLMs to uncover vulnerabilities. Five main sub-types are recognized in research.)*

- **Fuzzers** – Systematically or randomly generate inputs to discover vulnerabilities.  
  - **[LLMFuzzer](https://github.com/llm-fuzzer/LLMFuzzer)**
  - **[FuzzyAI](https://github.com/cyberark/FuzzyAI)**
  - **[GPTFuzz](https://github.com/sherdencooper/GPTFuzz)**

- **Prompt Injection Scanners** – Detect known prompt injection patterns and payloads.  
  - **[Promptmap](https://github.com/utkusen/promptmap)**

- **Comprehensive Security Testers** – Multi-module frameworks scanning for multiple vulnerability classes in one run (injection, leakage, jailbreak, unsafe output).  
  - **[Garak](https://github.com/NVIDIA/garak)**

- **Data Leakage Detectors** – Identify unintended disclosure of sensitive information.  
  - *(No dedicated open-source tool listed yet.)*

### Automated Red-Teaming Harnesses
*(Goal-driven, adaptive attack orchestrators that can chain tools like garak.)*
- **[PyRIT](https://github.com/Azure/PyRIT)** 
- **[DeepTeam](https://github.com/confident-ai/deepteam)** 
- **[PentestGPT](https://github.com/GreyDGL/PentestGPT)** 
- **[promptfoo](https://github.com/promptfoo/promptfoo)** 

### Benchmarks / Test Suites
*(Standardized datasets and scoring methods for resilience measurement.)*
- **[Purple Llama — CyberSecEval](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks)**
- **[AgentDojo](https://github.com/llm-benchmarks/agentdojo)** 
- **[JailbreakBench](https://github.com/JailbreakBench/jailbreakbench)**

### Data Security & Integrity — Model Artifact Scanning (static)
*Scan model files **before loading**; supply-chain hygiene.*

- **Protect AI — ModelScan** — Open-source serialized model scanner (Pickle/TF/Keras).  
  GitHub: https://github.com/protectai/modelscan - https://protectai.com/modelscan
- **HiddenLayer — Model Scanner** — Commercial artifact scanner - https://hiddenlayer.com/model-scanner/
- **Trail of Bits — Fickling** — Pickle decompiler/static analyzer for `.pkl`/`.pt`. - https://github.com/trailofbits/fickling
- **picklescan** — Lightweight Pickle scanner (fast triage). - https://github.com/mmaitre314/picklescan

### Model Training & Hardening (white-box/robustness)
*Attack/defense libraries for robustness research and training-time hardening.*

- **Foolbox** — Adversarial attacks for robustness research.  
  https://github.com/bethgelab/foolbox

### Model Evaluation & Adversarial Testing (white-box & general eval)
*Evaluate/defend against evasion, poisoning, extraction, inference attacks.*

- **Adversarial Robustness Toolbox (ART)** — Comprehensive attacks & defenses.  
  https://github.com/Trusted-AI/adversarial-robustness-toolbox
- **DeepEval** — LLM evaluation (hallucination, RAG, adversarial, bias).  
  https://github.com/deepeval/deepeval

### Model Deployment & Security Monitoring (agentic/RAG apps)
*Operational checks for agentic services; pre-deploy and runtime.*

- **Agentic Security** — Scanner for agent workflows and LLM apps (jailbreaks, fuzzing, multimodal issues).  
  https://github.com/msoedov/agentic_security

### Runtime Guardrails & DLP (defenses, not scanners)
*Filters/sanitizers to reduce leakage and unsafe content in production.*

- **LLM Guard** — Prompt/output DLP, PII redaction, PI resistance.  
  https://github.com/protectai/llm-guard
---

## [Podcasts](#podcasts)


- [**The MLSecOps Podcast**](https://podcasts.apple.com/us/podcast/the-mlsecops-podcast/id1679667447) – Insightful conversations with industry leaders and AI experts, exploring the fascinating world of machine learning security operations.

---

## Contributing

Contributions are welcome! If you have new resources, tools, or insights to add, feel free to submit a pull request.

This repository follows the **[Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)** guidelines.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under the **Creative Commons Zero v1.0 Universal** license.
