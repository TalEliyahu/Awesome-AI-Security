
## [An Automated Attack Investigation Approach Leveraging Threat-Knowledge-Augmented Large Language Models](https://arxiv.org/pdf/2509.01271)

### Prompt for Kill-Chain Annotation

You are an expert in Kill Chain knowledge, write the analysis. Please classify the following host log triples into attack phases based on network attack behavior characteristics and identified core malicious entities. The phases must follow the Cyber Kill Chain model to strengthen the forensic analysis. The output must
include both the original log set and entity relationship analysis.

Contexts:[malicious_entities],[sequences]

Task: 

1. Identify critical stages of the attack lifecycle (e.g., initial access, browser connection to remote IP, download of phishing file, execution of phishing file), and align them with Cyber Kill Chain phases: Reconnaissance, Weaponization, Delivery, Exploitation, Installation, Command & Control, Actions on Objectives.
2. Detect malicious file deployment patterns
3. Infer causality between the current and previous window based on behavioral continuity...
4. Analyze invocation relationships between entities.
5. Explicitly include the names of the relevant entities.
6. ...

Processing Rules: 

1. Strictly preserve the original temporal order.
2. Merge operations with the same attack intent into a single phase.
3. Separate different attack vectors into independent phases.
4. Merge multiple actions triggered by the same entity
5. evidence_set must fully retain the original log entries.
6. Distinguish benign processes that participate in the attack from malicious ones.
7. ...

Output Format: Return the result as a JSON array...


### Prompt for Causal Reasoning

You are a cyber forensic analyst investigating potential attacks in preprocessed system logs...
Given a sequence of attack-related behavior records...
The logs are structured as (subject, action, object) triple...

Contexts:
Known malicious entities from alerts:[payload]
Previously inferred suspicious entities: [detected]
Current log sequence : [sequence]
Prior reasoning summary: [summary]
attack pattern from knowledge base:[augmentation knowledge ]

Task:

1. Analyze the current log sequence in temporal order...
2. Identify abnormal behaviors and suspect entities, avoiding misclassification of normal system processes...
3. Infer causality between the current and previous window based on behavioral continuity...
4. ...

Answer:
Output Format: Return the result as a JSON array...

### Prompt for Attack Report Generation

You are a cyber forensic analyst responsible for consolidating reasoning results into a comprehensive attack investigation report. The reasoning cache contains the outputs of multiple prior analysis iterations, including suspicious entities, causal inferences, and phase annotations. Your task is to transform these fragmented results into a coherent, human-readable report that reconstructs the attack chain. Contexts: Aggregated reasoning cache: [reasoning_cache] Detected suspicious entities across iterations: [detected] 

Task: 

1. Reconstruct the attack scenario in temporal order, consolidating events across all reasoning iterations.
2. Organize the scenario into Kill Chain phases (e.g., Initial Access, Persistence, Lateral Movement, Exfiltration).
3. Summarize abnormal behaviors and their causal relationships, highlighting how each suspicious entity contributed to the attack progression.
4. Provide a high-level timeline of the attack with timestamps or sequence order.
5. ...

Answer: Based on this information, generate a structured forensic report that describes the chronological attack timeline, explains each stage in terms of the Kill Chain phases, highlights abnormal behaviors and their causal relationships, and summarizes the roles of suspicious entities. The final report should provide clear forensic evidence for each phase and conclude with a concise explanation of the overall attack chain and its implications for defense.

### Prompt for Attack Report Generation

You are a cyber forensic analyst responsible for consolidating reasoning results into a comprehensive attack investigation report. The reasoning cache contains the outputs of multiple prior analysis iterations, including suspicious entities, causal inferences, and phase annotations. Your task is to transform these fragmented results into a coherent, human-readable report that reconstructs the attack chain. Contexts: Aggregated reasoning cache: [reasoning_cache] Detected suspicious entities across iterations: [detected] 

Task: 

1. Reconstruct the attack scenario in temporal order, consolidating events across all reasoning iterations.
2. Organize the scenario into Kill Chain phases (e.g., Initial Access, Persistence, Lateral Movement, Exfiltration).
3. Summarize abnormal behaviors and their causal relationships, highlighting how each suspicious entity contributed to the attack progression.
4. Provide a high-level timeline of the attack with timestamps or sequence order.
5. ...

Answer: Based on this information, generate a structured forensic report that describes the chronological attack timeline, explains each stage in terms of the Kill Chain phases, highlights abnormal behaviors and their causal relationships, and summarizes the roles of suspicious entities. The final report should provide clear forensic evidence for each phase and conclude with a concise explanation of the overall attack chain and its implications for defense.

