# Research Papers

A curated list of recent research relevant to AI security.

## August 2025

- 📖 **[DIRF: A Framework for Digital Identity Protection and Clone Governance in Agentic AI Systems](https://www.arxiv.org/pdf/2508.01997)** — Proposes a Digital Identity Rights Framework to govern biometric/behavioral likeness, detection, and lawful use of AI-generated clones.

- 📖 **[LLMs in the SOC: An Empirical Study of Human-AI Collaboration in Security Operations Centres](https://arxiv.org/pdf/2508.18947)** — Longitudinal study (3,090 queries, 45 analysts, 10 months) finds LLMs aid sensemaking/context-building while humans retain decision authority.

- 📖 **[School of Reward Hacks: Hacking harmless tasks generalizes to misaligned behavior in LLMs](https://arxiv.org/pdf/2508.17511)** — Trains models to “reward hack” on low-stakes tasks and shows behaviors generalize, illuminating misalignment risks in practice.

- 📖 **[PentestJudge: Judging Agent Behavior Against Operational Requirements](https://arxiv.org/pdf/2508.02921)** — LLM-as-judge framework to evaluate pentesting agents against operational criteria, calibrated to human expert ground truth.

- 📖 **[Incident Analysis for AI Agents](https://arxiv.org/pdf/2508.14231v1)** — Argues for richer, privacy-aware incident reporting (e.g., prompts, tool logs) to understand and prevent harmful agent incidents.

- 📖 **[On the Security and Privacy of Federated Learning: A Survey](https://www.arxiv.org/abs/2508.13730)** — Comprehensive review of >200 papers on FL attacks/defenses, frameworks, applications, and open directions.

- 📖 **[A Guide to Stakeholder Analysis for Cybersecurity Researchers](https://arxiv.org/pdf/2508.14796)** — Practical ethics guide mapping stakeholder types to research methods with worked examples for security studies.

- 📖 **[In-Training Defenses against Emergent Misalignment in Language Models](https://arxiv.org/pdf/2508.06249)** — Studies safeguards during fine-tuning (including hosted fine-tune APIs) to mitigate emergent misalignment beyond the target domain.

- 📖 **[Improving Google A2A Protocol: Protecting Sensitive Data and Mitigating Unintended Harms in Multi-Agent Systems](https://arxiv.org/pdf/2505.12490v3)** — Identifies protocol weaknesses and proposes zero-trust-inspired enhancements for consent, auth, and data-flow transparency.

- 📖 **[Searching for Privacy Risks in LLM Agents via Simulation](https://arxiv.org/pdf/2508.10880)** — Simulation framework to probe privacy failures when multiple agents collaborate and exchange sensitive information.

- 📖 **[Autonomous Blue-Team LLM Agent for Web Attack Forensics](https://arxiv.org/pdf/2508.20643)** — “CyberSleuth” agent reconstructs web intrusions from traces/logs, identifies CVEs, and generates structured forensic reports.

- 📖 **[Advancing Autonomous Incident Response: Leveraging LLMs and Cyber Threat Intelligence](https://arxiv.org/pdf/2508.10677)** — RAG-based IR pipeline that fuses CTI retrieval with alert context to automate enrichment and decision support.

- 📖 **[Securing Agentic AI: Threat Modeling and Risk Analysis for Network Monitoring Agentic AI System](https://arxiv.org/pdf/2508.10043)** — Applies a MAESTRO-style 7-layer model to enumerate threats/risks introduced by network-monitoring agents.

- 📖 **[Ransomware 3.0: Self-Composing and LLM-Orchestrated](https://arxiv.org/pdf/2508.20444v1)** — Conceptualizes end-to-end LLM-driven ransomware that probes, plans, deploys payloads, and personalizes extortion autonomously.

- 📖 **[Deep Ignorance: Filtering Pretraining Data Builds Tamper-Resistant Safeguards into Open-Weight LLMs](https://arxiv.org/pdf/2508.06601)** — Tests whether filtering unsafe pretraining data (e.g., biorisk) can reduce downstream hazardous capabilities in open models.

- 📖 **[Invitation Is All You Need! Promptware Attacks Against LLM-Powered Assistants in Production Are Practical and Dangerous](https://arxiv.org/pdf/2508.12175)** — Demonstrates “promptware” attacks that exploit integration surfaces of production assistants; releases site with examples.

- 📖 **[Training Language Model Agents to Find Vulnerabilities with CTF-DOJO](https://arxiv.org/pdf/2508.18370)** — Introduces CTF-DOJO, an execution environment with hundreds of Dockerized CTF challenges (from pwn.college) to train and evaluate vuln-finding agents end-to-end.

---

## July 2025

- 📖 **[We Urgently Need Privilege Management in MCP: A Measurement of API Usage in MCP Ecosystems](https://arxiv.org/abs/2507.06250)** — Measurement of 2,562 MCP servers across 23 categories shows heavy use of network/system/file APIs with over-privileged access and weak isolation, creating tampering and data-exfiltration risks.

- 📖 **[TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management in LLM-based Multi-Agent Systems](https://arxiv.org/abs/2506.04133)** — Survey of lifecycle safeguards for agentic systems (prompt infection, memory poisoning, collusion, tool misuse) aligned to NIST AI RMF and OWASP LLM Top 10.

- 📖 **[AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models](https://arxiv.org/abs/2506.14682)** — Benchmark of 70 CTF-style challenges for offensive tasks; headline results include strong prompt-injection performance but weak system exploitation/model inversion.

- 📖 **[A Survey of LLM-Driven AI Agent Communication: Protocols, Security Risks, and Defense Countermeasures](https://arxiv.org/abs/2506.19676)** — Reviews agent communication protocols (e.g., MCP, A2A), stages, threat surfaces, and mitigations such as sandboxing and monitoring.

- 📖 **[RepoAudit: An Autonomous LLM-Agent for Repository-Level Code Auditing](https://arxiv.org/abs/2501.18160)** — Memory-augmented agent with validator for end-to-end repo audits; reports 78.43% precision and 185 new bugs found (most confirmed/fixed).

- 📖 **[Decompiling Smart Contracts with a Large Language Model](https://arxiv.org/pdf/2506.19624)** — LLM-based semantic analysis of EVM bytecode to surface vulnerabilities and malicious logic amid low verification rates.

- 📖 **[Dynamic Risk Assessments for Offensive Cybersecurity Agents](https://arxiv.org/pdf/2505.18384)** — Argues static evaluations understate risk; proposes compute-aware, continuously updated risk scoring during agent operations.

- 📖 **[When LLMs Autonomously Attack](https://engineering.cmu.edu/news-events/news/2025/07/24-when-llms-autonomously-attack.html)** — CMU demonstrates LLMs planning/executing cyberattacks in enterprise-grade networks; implications for defense and governance.

- 📖 **[ETrace: Event-Driven Vulnerability Detection in Smart Contracts via LLM-Based Trace Analysis](https://arxiv.org/pdf/2506.15790)** — Event-centric trace reasoning enables vuln detection without source code.

- 📖 **[BaxBench: Can LLMs Generate Correct and Secure Backends?](https://arxiv.org/abs/2502.11844) ([PDF](https://arxiv.org/pdf/2502.11844))** — 392-task benchmark on production-grade backend generation; even “correct” code often remains exploitable, with larger drops on less common frameworks.

- 📖 **[Autonomous AI-based Cybersecurity Framework for Critical Infrastructure](https://arxiv.org/abs/2507.07416)** — Hybrid framework for real-time vuln detection, threat modeling, and automated remediation across energy/health/transport/water sectors.

- 📖 **[SafeGenBench: A Benchmark Framework for Security Vulnerability Detection in LLM-Generated Code](https://arxiv.org/abs/2506.05692)** — 558 tasks, 44 CWEs, 13 languages; zero-shot “secure accuracy” ~37%, rising to ~74% with few-shot; memory-safety best, insecure configuration worst.

- 📖 **[Red Teaming AI Red Teaming](https://arxiv.org/pdf/2507.05538v1)** — Critical examination of AI red-teaming practice, scope, and methodology; highlights gaps and standardization needs.

- 📖 **[From Prompt Injections to Protocol Exploits: Threats in LLM-Powered AI Agent Workflows](https://arxiv.org/abs/2506.23260)** — Unified threat model spanning input manipulation, model compromise, privacy/system attacks, and protocol exploits (MCP/ACP/A2A).

- 📖 **[Vulnerability Detection Model using LLM and Code Chunk](https://arxiv.org/pdf/2506.19453)** — Function-level vuln localization aims to reduce OSS supply-chain risk; discusses distinguishing true fixes from unrelated patches.

- 📖 **[Trivial Trojans: How Minimal MCP Servers Enable Cross-Tool Exfiltration of Sensitive Data](https://arxiv.org/abs/2507.19880)** — PoC shows benign-looking “weather” MCP server can discover and abuse other tools to exfiltrate data via MCP trust boundaries.

- 📖 **[Security Challenges in AI Agent Deployment: Insights from a Large-Scale Public Competition](https://arxiv.org/abs/2507.20526)** — Results from red-teaming 22 frontier agents across 44 scenarios (1.8M prompt injections, 60k+ violations); introduces the ART benchmark.

---

## June 2025

- 📖 **[AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models](https://arxiv.org/abs/2506.14682)** — Benchmark suite and metrics for assessing LLMs’ autonomous red-team capabilities across realistic adversarial tasks.

- 📖 **[VulBinLLM: LLM-powered Vulnerability Detection for Stripped Binaries](https://arxiv.org/abs/2505.22010)** — Uses LLM reasoning over disassembly and program artifacts to detect vulnerabilities even when symbols are removed.

- 📖 **[CAI: An Open, Bug Bounty-Ready Cybersecurity AI](https://arxiv.org/abs/2504.06017)** — Open system that orchestrates LLMs for bug bounty workflows (recon, triage, exploit ideation) with reproducible evaluations.

- 📖 **[Dynamic Risk Assessments for Offensive Cybersecurity Agents](https://arxiv.org/abs/2505.18384)** — Proposes real-time risk scoring and governance for AI agents during offensive security operations.

- 📖 **[Design Patterns for Securing LLM Agents against Prompt Injections](https://arxiv.org/abs/2506.08837)** — Catalog of defensive patterns (isolation, allow-lists, mediation, auditing) to harden agent architectures.

- 📖 **[PANDAGUARD: Systematic Evaluation of LLM Safety against Jailbreaking Attacks](https://arxiv.org/abs/2505.13862)** — A standardized framework to measure jailbreak robustness across models and attack families.

- 📖 **[Lessons from Defending Gemini Against Indirect Prompt Injections](https://arxiv.org/abs/2505.14534)** — Case studies and mitigations for cross-context (RAG/tools) prompt injection discovered in the wild.

- 📖 **[Enterprise-Grade Security for the Model Context Protocol (MCP): Frameworks and Mitigation Strategies](https://arxiv.org/abs/2504.08623)** — Security controls for MCP deployments, including sandboxing, zero-trust tool access, and per-request policies.

- 📖 **[Securing AI Agents with Information-Flow Control](https://arxiv.org/abs/2505.23643)** — Applies IFC to constrain data movement across agent tools, memory, and environments to prevent exfiltration and misuse.

- 📖 **[Common Corpus: The Largest Collection of Ethical Data for LLM Pre-Training](https://arxiv.org/abs/2506.01732)** — Introduces a large, license-screened open pretraining corpus designed for regulatory compliance.

- 📖 **[A Novel Zero-Trust Identity Framework for Agentic AI: Decentralized Authentication and Fine-Grained Access Control](https://arxiv.org/abs/2505.19301)** — Identity and authorization architecture tailored to multi-agent ecosystems with least-privilege access.

- 📖 **[OS-HARM: A Benchmark for Measuring Safety of Computer Use Agents](https://arxiv.org/pdf/2506.14866)** — Introduces a safety benchmark for GUI-operating agents, highlighting overlooked risks in “computer use” systems.

- 📖 **[Malicious AI Models Undermine Software Supply-Chain Security](https://cacm.acm.org/research/malicious-ai-models-undermine-software-supply-chain-security/)** — CACM research article on how malicious/poisoned models create software supply-chain risks and suggested mitigations.

---

## May 2025

- 📖 **[Understanding LLM Supply Chains](https://arxiv.org/abs/2504.20763)** — A deep mapping of 15,000+ open-source packages reveals how a small number of libraries (like transformers, langchain) dominate the ecosystem. A single vulnerability in one core package can indirectly affect 1,000+ others via transitive dependencies. Most issues go unreported through formal CVEs.

- 📖 **[Full-Stack Safety Survey for LLMs](https://arxiv.org/abs/2504.15585)** — The first end-to-end review of safety challenges across the LLM lifecycle — from data collection to commercialization. Synthesizes over 800 papers, highlights risks in alignment, deployment, and model editing, and proposes forward-looking safeguards.

- 📖 **[The Leaderboard Illusion](https://arxiv.org/pdf/2504.20879)** — A multi-institutional audit of Chatbot Arena exposes manipulation risks, duplicated prompts, silent model removal, and data inequality. Open-weight models receive less training data and sampling attention, distorting perception of model quality.

- 📖 **[LLM Agent Privacy & Security Survey](https://arxiv.org/html/2407.19354v1)** — Categorizes nine key vulnerabilities in LLM agents, from hallucinations and knowledge poisoning to data leakage and agent manipulation. Case studies reveal the real-world impacts and gaps in current defenses.

- 📖 **[Control Levels for LLM Agents](https://arxiv.org/abs/2504.05259)** — Introduces a 5-level framework (ACLs 1–5) to align security measures with AI agent capabilities. Offers structured control evaluation rules and red teaming affordances for increasingly powerful agents.

- 📖 **[Package Hallucination in LLMs](https://arxiv.org/abs/2406.10279)** — LLMs frequently invent nonexistent libraries (e.g., `pip install xyz`) — a risk now named *slopsquatting*. Adversaries can register these fake packages with malware. Study shows 19.7% hallucination rate across 16 LLMs and 576K samples.

- 📖 **[Enterprise-Grade MCP Security](https://arxiv.org/abs/2504.08623)** — AWS-backed paper on securing AI toolchains using the Model Context Protocol. Recommends sandboxing, zero-trust design, and per-request access policies to mitigate tool poisoning, data leaks, and exfiltration.

- 📖 **[Can LLMs Classify CVEs?](https://arxiv.org/pdf/2504.10713v1)** — Proposes a hybrid CVSS scoring pipeline combining Gemma 3 for objective fields with MiniLM+XGBoost for subjective ones, achieving 84% accuracy.

- 📖 **[Open Problems in Technical AI Governance](https://arxiv.org/abs/2407.14981)** — Maps unresolved challenges in verifying, monitoring, and securing AI systems — from data traceability to model access policies and third-party audits.

- 📖 **[RAG LLMs Are Not Safer](https://arxiv.org/pdf/2504.18041)** — Retrieval-augmented generation changes model behavior and risk profile. Even safe docs + safe models can yield unsafe outputs. Study shows red teaming methods are less effective in RAG settings.

