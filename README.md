# Awesome AI Security 🛡️

> Curated resources, research, and tools for securing AI systems.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

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

📌 *(To be added – Public datasets useful for AI security research and adversarial ML testing.)*

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

📌 *(More working groups to be added.)*

---

## Additional AI Security Resources

- [LLM Security](http://llmsecurity.net)
- [Vinija AI](http://vinija.ai/models/LLM/)

---

## Newsletter

- [Adversarial AI Digest](https://www.linkedin.com/newsletters/adversarial-ai-digest-7298813894498598912/)

---

## Conferences and Events

- [AI Village (DEF CON)](https://aivillage.org/)
- [Black Hat AI Summit](https://www.blackhat.com/)

---

## Reports and Research

📌 *(More to be added – A collection of AI security reports, white papers, and academic studies.)*

---

## CTF Challenges

- [AI GOAT](https://github.com/dhammon/ai-goat) – A set of LLM security challenges focused on identifying and exploiting vulnerabilities in AI systems.
- [Gandalf CTF](https://gandalf.lakera.ai/) – A challenge where participants attempt to extract hidden passphrases from an evolving AI model through prompt engineering techniques.
- [DamnVulnerableLLMApplication-Demo](https://github.com/greshake/DamnVulnerableLLMApp) – A project designed for security researchers to practice LLM hacking techniques and for AI companies to improve the security of their models and systems.

---

## Tools

### Data Security & Integrity  
*(Ensuring the integrity, provenance, and security of training/testing data.)*  
- *(No tools currently listed in this category.)*  

### Model Training & Hardening  
*(Protecting models from adversarial attacks during training.)*  
- **[Foolbox](https://github.com/bethgelab/foolbox)** – A Python library for running adversarial attacks against machine learning models, including deep neural networks.  

### Model Evaluation & Adversarial Testing  
*(Assessing AI model security posture before deployment.)*  
- **[Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)** – Provides tools to defend and evaluate machine learning models against adversarial threats, including evasion, poisoning, extraction, and inference attacks.
- **[DeepEval](https://github.com/deepeval/deepeval)** – An LLM evaluation framework designed for testing large language models. Supports hallucination detection, bias analysis, RAG assessment, adversarial robustness testing, and model benchmarking.  
- **[RobustBench](https://github.com/RobustBench/robustbench)** – A standardized adversarial robustness benchmark that evaluates AI models against adversarial perturbations, common corruptions, and adaptive attacks.
- **[PyRIT](https://github.com/Azure/PyRIT)** – The Python Risk Identification Tool for generative AI (PyRIT) is an open-source framework built to empower security professionals and engineers to proactively identify risks in generative AI systems.  

### Model Deployment & Security Monitoring  
*(Ensuring secure AI model deployment and detecting vulnerabilities in operational environments.)*  
- **[Agentic Security](https://github.com/msoedov/agentic_security)** – An open-source vulnerability scanner for Agent Workflows and Large Language Models (LLMs). Helps protect AI systems from jailbreaks, fuzzing, and multimodal attacks.


---

## Contributing

Contributions are welcome! If you have new resources, tools, or insights to add, feel free to submit a pull request.

This repository follows the **[Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)** guidelines.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under the **Creative Commons Zero v1.0 Universal** license.
