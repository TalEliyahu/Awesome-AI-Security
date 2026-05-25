[English](Research_Papers.md) | 简体中文

> 说明：本中文对应版保留资源官方名称、链接和原有排序，便于与英文版对照维护。

# 研究论文

与 AI 安全相关的近期研究精选列表。

## 目录
- [February 2026](#february-2026)
- [August 2025](#august-2025)
- [July 2025](#july-2025)
- [June 2025](#june-2025)
- [May 2025](#may-2025)

## 2026 年 3 月

- 📖 **[Internal Safety Collapse in Frontier Large Language Models](https://arxiv.org/abs/2603.23509)** — 揭示一种新的安全失效模式：LLM 在完成正常专业任务时可能附带生成有害内容，无需对抗提示。该方法在 pass@3 下可越狱多种前沿 LLM（Claude Opus 4.6、GPT-5.4、Gemini 3.1 Pro），覆盖黑盒、跨领域、单轮、ICL 和智能体攻击模式。[[Code](https://github.com/wuyoscar/ISC-Bench)]

---

## 2026 年 2 月

- 📖 **[Breaking Agent Backbones: Evaluating the Security of Backbone LLMs in AI Agents](https://arxiv.org/abs/2510.22620)** — 提出“威胁快照”以识别基础 LLM 漏洞如何传播为智能体级风险；b³ 基准用 194,331 个众包对抗攻击评估 34 个 LLM，并发现推理能力而非模型规模与安全性相关。 [ICLR 2026]

---

## 2025 年 8 月

- 📖 **[DIRF: A Framework for Digital Identity Protection and Clone Governance in Agentic AI Systems](https://www.arxiv.org/pdf/2508.01997)** — 提出数字身份权利框架，用于治理生物特征/行为相似性、检测以及 AI 生成克隆的合法使用。

- 📖 **[LLMs in the SOC: An Empirical Study of Human-AI Collaboration in Security Operations Centres](https://arxiv.org/pdf/2508.18947)** — 纵向研究（3,090 次查询、45 名分析师、10 个月）发现 LLM 有助于态势理解和上下文构建，但决策权仍由人类保留。

- 📖 **[School of Reward Hacks: Hacking harmless tasks generalizes to misaligned behavior in LLMs](https://arxiv.org/pdf/2508.17511)** — 在低风险任务上训练模型进行“奖励黑客”行为，并展示该行为可泛化，从实践角度揭示错位风险。

- 📖 **[PentestJudge: Judging Agent Behavior Against Operational Requirements](https://arxiv.org/pdf/2508.02921)** — 使用 LLM-as-judge 框架按操作性标准评估渗透测试智能体，并以人类专家标注进行校准。

- 📖 **[Incident Analysis for AI Agents](https://arxiv.org/pdf/2508.14231v1)** — 主张更丰富且保护隐私的事件报告（如提示词、工具日志），以理解并预防有害智能体事件。

- 📖 **[On the Security and Privacy of Federated Learning: A Survey](https://www.arxiv.org/abs/2508.13730)** — 综合综述 200 多篇关于联邦学习攻击/防御、框架、应用和开放方向的论文。

- 📖 **[A Guide to Stakeholder Analysis for Cybersecurity Researchers](https://arxiv.org/pdf/2508.14796)** — 面向网络安全研究的实用伦理指南，将利益相关方类型映射到研究方法，并提供安全研究示例。

- 📖 **[In-Training Defenses against Emergent Misalignment in Language Models](https://arxiv.org/pdf/2508.06249)** — 研究微调期间的保护措施（包括托管微调 API），以缓解超出目标领域的新兴错位行为。

- 📖 **[Improving Google A2A Protocol: Protecting Sensitive Data and Mitigating Unintended Harms in Multi-Agent Systems](https://arxiv.org/pdf/2505.12490v3)** — 识别协议弱点，并提出受零信任启发的增强方案，覆盖同意、认证和数据流透明度。

- 📖 **[Searching for Privacy Risks in LLM Agents via Simulation](https://arxiv.org/pdf/2508.10880)** — 提出仿真框架，用于探测多个智能体协作和交换敏感信息时的隐私失效。

- 📖 **[Autonomous Blue-Team LLM Agent for Web Attack Forensics](https://arxiv.org/pdf/2508.20643)** — “CyberSleuth” 智能体从痕迹/日志重建 Web 入侵，识别 CVE，并生成结构化取证报告。

- 📖 **[Advancing Autonomous Incident Response: Leveraging LLMs and Cyber Threat Intelligence](https://arxiv.org/pdf/2508.10677)** — 基于 RAG 的事件响应流水线，将 CTI 检索与告警上下文结合，自动完成信息丰富和决策支持。

- 📖 **[Securing Agentic AI: Threat Modeling and Risk Analysis for Network Monitoring Agentic AI System](https://arxiv.org/pdf/2508.10043)** — 应用 MAESTRO 风格的 7 层模型，枚举网络监控智能体引入的威胁和风险。

- 📖 **[Ransomware 3.0: Self-Composing and LLM-Orchestrated](https://arxiv.org/pdf/2508.20444v1)** — 概念化端到端 LLM 驱动勒索软件，可自主探测、规划、部署载荷并个性化勒索。

- 📖 **[Deep Ignorance: Filtering Pretraining Data Builds Tamper-Resistant Safeguards into Open-Weight LLMs](https://arxiv.org/pdf/2508.06601)** — 测试过滤不安全预训练数据（如生物风险内容）是否可降低开放权重模型的下游危险能力。

- 📖 **[Invitation Is All You Need! Promptware Attacks Against LLM-Powered Assistants in Production Are Practical and Dangerous](https://arxiv.org/pdf/2508.12175)** — 展示利用生产环境助手集成面的“promptware”攻击，并发布示例站点。

- 📖 **[Training Language Model Agents to Find Vulnerabilities with CTF-DOJO](https://arxiv.org/pdf/2508.18370)** — 介绍 CTF-DOJO，一个包含数百个 Docker 化 CTF 挑战（来自 pwn.college）的执行环境，用于端到端训练和评估漏洞发现智能体。

---

## 2025 年 7 月

- 📖 **[We Urgently Need Privilege Management in MCP: A Measurement of API Usage in MCP Ecosystems](https://arxiv.org/abs/2507.06250)** — 对 23 个类别中 2,562 个 MCP 服务器的测量显示，网络/系统/文件 API 被大量使用，且存在过度权限和弱隔离，带来篡改和数据外泄风险。

- 📖 **[TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management in LLM-based Multi-Agent Systems](https://arxiv.org/abs/2506.04133)** — 综述智能体系统生命周期防护措施（提示感染、记忆投毒、串通、工具滥用），并与 NIST AI RMF 和 OWASP LLM Top 10 对齐。

- 📖 **[AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models](https://arxiv.org/abs/2506.14682)** — 包含 70 个 CTF 风格进攻任务的基准；主要结果显示提示注入能力较强，但系统利用和模型反演较弱。

- 📖 **[A Survey of LLM-Driven AI Agent Communication: Protocols, Security Risks, and Defense Countermeasures](https://arxiv.org/abs/2506.19676)** — 回顾智能体通信协议（如 MCP、A2A）、阶段、威胁面，以及沙箱和监控等缓解措施。

- 📖 **[RepoAudit: An Autonomous LLM-Agent for Repository-Level Code Auditing](https://arxiv.org/abs/2501.18160)** — 带验证器的记忆增强智能体，用于端到端仓库审计；报告 78.43% 精确率并发现 185 个新缺陷（多数已确认/修复）。

- 📖 **[Decompiling Smart Contracts with a Large Language Model](https://arxiv.org/pdf/2506.19624)** — 使用 LLM 对 EVM 字节码进行语义分析，在源码验证率较低的情况下发现漏洞和恶意逻辑。

- 📖 **[Dynamic Risk Assessments for Offensive Cybersecurity Agents](https://arxiv.org/pdf/2505.18384)** — 指出静态评估会低估风险，并提出在智能体运行期间进行计算感知、持续更新的风险评分。

- 📖 **[When LLMs Autonomously Attack](https://engineering.cmu.edu/news-events/news/2025/07/24-when-llms-autonomously-attack.html)** — CMU 展示 LLM 在企业级网络中规划并执行网络攻击，对防御和治理具有启示。

- 📖 **[ETrace: Event-Driven Vulnerability Detection in Smart Contracts via LLM-Based Trace Analysis](https://arxiv.org/pdf/2506.15790)** — 以事件为中心的 trace 推理可在无源码情况下进行漏洞检测。

- 📖 **[BaxBench: Can LLMs Generate Correct and Secure Backends?](https://arxiv.org/abs/2502.11844) ([PDF](https://arxiv.org/pdf/2502.11844))** — 面向生产级后端生成的 392 项任务基准；即使“正确”的代码也常可被利用，在较少见框架上的表现下降更明显。

- 📖 **[Autonomous AI-based Cybersecurity Framework for Critical Infrastructure](https://arxiv.org/abs/2507.07416)** — 面向能源、医疗、交通和水务等领域的混合框架，用于实时漏洞检测、威胁建模和自动化修复。

- 📖 **[SafeGenBench: A Benchmark Framework for Security Vulnerability Detection in LLM-Generated Code](https://arxiv.org/abs/2506.05692)** — 包含 558 项任务、44 个 CWE、13 种语言；零样本“安全准确率”约 37%，少样本提升至约 74%；内存安全表现最好，不安全配置最差。

- 📖 **[Red Teaming AI Red Teaming](https://arxiv.org/pdf/2507.05538v1)** — 批判性审视 AI 红队实践、范围和方法，指出差距与标准化需求。

- 📖 **[From Prompt Injections to Protocol Exploits: Threats in LLM-Powered AI Agent Workflows](https://arxiv.org/abs/2506.23260)** — 提出统一威胁模型，覆盖输入操纵、模型破坏、隐私/系统攻击和协议利用（MCP/ACP/A2A）。

- 📖 **[Vulnerability Detection Model using LLM and Code Chunk](https://arxiv.org/pdf/2506.19453)** — 函数级漏洞定位旨在降低 OSS 供应链风险，并讨论如何区分真实修复与无关补丁。

- 📖 **[Trivial Trojans: How Minimal MCP Servers Enable Cross-Tool Exfiltration of Sensitive Data](https://arxiv.org/abs/2507.19880)** — PoC 显示看似无害的“天气”MCP 服务器可发现并滥用其他工具，通过 MCP 信任边界外泄数据。

- 📖 **[Security Challenges in AI Agent Deployment: Insights from a Large-Scale Public Competition](https://arxiv.org/abs/2507.20526)** — 汇总对 22 个前沿智能体、44 个场景的红队结果（180 万次提示注入、6 万余次违规），并介绍 ART 基准。

---

## 2025 年 6 月

- 📖 **[AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models](https://arxiv.org/abs/2506.14682)** — 用于评估 LLM 在真实对抗任务中自主红队能力的基准套件和指标。

- 📖 **[VulBinLLM: LLM-powered Vulnerability Detection for Stripped Binaries](https://arxiv.org/abs/2505.22010)** — 利用 LLM 对反汇编和程序工件进行推理，即使符号被移除也能检测漏洞。

- 📖 **[CAI: An Open, Bug Bounty-Ready Cybersecurity AI](https://arxiv.org/abs/2504.06017)** — 面向漏洞赏金工作流（侦察、分诊、利用构思）的开放系统，可编排 LLM 并提供可复现实验评估。

- 📖 **[Dynamic Risk Assessments for Offensive Cybersecurity Agents](https://arxiv.org/abs/2505.18384)** — 提出在进攻性安全操作期间对 AI 智能体进行实时风险评分和治理。

- 📖 **[Design Patterns for Securing LLM Agents against Prompt Injections](https://arxiv.org/abs/2506.08837)** — 汇总用于加固智能体架构的防御模式（隔离、允许列表、中介、审计）。

- 📖 **[PANDAGUARD: Systematic Evaluation of LLM Safety against Jailbreaking Attacks](https://arxiv.org/abs/2505.13862)** — 用于衡量不同模型和攻击族越狱鲁棒性的标准化框架。

- 📖 **[Lessons from Defending Gemini Against Indirect Prompt Injections](https://arxiv.org/abs/2505.14534)** — 针对野外发现的跨上下文（RAG/工具）提示注入，提供案例研究和缓解措施。

- 📖 **[Enterprise-Grade Security for the Model Context Protocol (MCP): Frameworks and Mitigation Strategies](https://arxiv.org/abs/2504.08623)** — 面向 MCP 部署的安全控制，包括沙箱、零信任工具访问和逐请求策略。

- 📖 **[Securing AI Agents with Information-Flow Control](https://arxiv.org/abs/2505.23643)** — 应用信息流控制约束智能体工具、记忆和环境之间的数据移动，以防止外泄和滥用。

- 📖 **[Common Corpus: The Largest Collection of Ethical Data for LLM Pre-Training](https://arxiv.org/abs/2506.01732)** — 介绍一个大型、经过许可筛选的开放预训练语料库，面向监管合规设计。

- 📖 **[A Novel Zero-Trust Identity Framework for Agentic AI: Decentralized Authentication and Fine-Grained Access Control](https://arxiv.org/abs/2505.19301)** — 面向多智能体生态的身份与授权架构，支持最小权限访问。

- 📖 **[OS-HARM: A Benchmark for Measuring Safety of Computer Use Agents](https://arxiv.org/pdf/2506.14866)** — 提出面向 GUI 操作智能体的安全基准，强调“计算机使用”系统中被忽视的风险。

- 📖 **[Malicious AI Models Undermine Software Supply-Chain Security](https://cacm.acm.org/research/malicious-ai-models-undermine-software-supply-chain-security/)** — CACM 研究文章，讨论恶意/投毒模型如何带来软件供应链风险，并提出缓解建议。

---

## 2025 年 5 月

- 📖 **[Understanding LLM Supply Chains](https://arxiv.org/abs/2504.20763)** — 对 15,000 多个开源包的深入映射显示，少数库（如 transformers、langchain）主导生态。一个核心包漏洞可通过传递依赖间接影响 1,000 多个其他包，且多数问题未通过正式 CVE 报告。

- 📖 **[Full-Stack Safety Survey for LLMs](https://arxiv.org/abs/2504.15585)** — 首个覆盖 LLM 生命周期（从数据收集到商业化）安全挑战的端到端综述；综合 800 多篇论文，强调对齐、部署和模型编辑风险，并提出前瞻性防护。

- 📖 **[The Leaderboard Illusion](https://arxiv.org/pdf/2504.20879)** — 多机构对 Chatbot Arena 的审计揭示操纵风险、重复提示、静默移除模型和数据不平等。开放权重模型获得更少训练数据和采样关注，扭曲了对模型质量的认知。

- 📖 **[LLM Agent Privacy & Security Survey](https://arxiv.org/html/2407.19354v1)** — 将 LLM 智能体中的九类关键漏洞分类，覆盖幻觉、知识投毒、数据泄露和智能体操纵；案例研究揭示现实影响和当前防御缺口。

- 📖 **[Control Levels for LLM Agents](https://arxiv.org/abs/2504.05259)** — 提出 5 级框架（ACLs 1-5），将安全措施与 AI 智能体能力对齐；为能力不断增强的智能体提供结构化控制评估规则和红队支持。

- 📖 **[Package Hallucination in LLMs](https://arxiv.org/abs/2406.10279)** — LLM 经常编造不存在的库（如 `pip install xyz`），该风险被称为 *slopsquatting*。攻击者可注册这些虚假包并植入恶意软件；研究显示 16 个 LLM、57.6 万个样本中的幻觉率为 19.7%。

- 📖 **[Enterprise-Grade MCP Security](https://arxiv.org/abs/2504.08623)** — AWS 支持的论文，讨论使用 Model Context Protocol 保护 AI 工具链；建议采用沙箱、零信任设计和逐请求访问策略来缓解工具投毒、数据泄露和外泄。

- 📖 **[Can LLMs Classify CVEs?](https://arxiv.org/pdf/2504.10713v1)** — 提出混合 CVSS 评分流水线，用 Gemma 3 处理客观字段、MiniLM+XGBoost 处理主观字段，准确率达到 84%。

- 📖 **[Open Problems in Technical AI Governance](https://arxiv.org/abs/2407.14981)** — 梳理验证、监控和保护 AI 系统中的未解挑战，覆盖数据可追溯性、模型访问策略和第三方审计。

- 📖 **[RAG LLMs Are Not Safer](https://arxiv.org/pdf/2504.18041)** — 检索增强生成会改变模型行为和风险画像。即使安全文档加安全模型也可能产生不安全输出；研究显示红队方法在 RAG 场景下效果较弱。

