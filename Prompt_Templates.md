## Prompt for Kill-Chain Annotation

You are an expert in Kill Chain knowledge, write the
analysis. Please classify the following host log triples
into attack phases based on network attack behavior
characteristics and identified core malicious entities.
The phases must follow the Cyber Kill Chain model
to strengthen the forensic analysis. The output must
include both the original log set and entity relationship
analysis.

Contexts:[malicious_entities],[sequences]

Task: 

1. Identify critical stages of the attack lifecycle (e.g., initial access, browser connection to remote
IP, download of phishing file, execution of phishing
file), and align them with Cyber Kill Chain phases:
Reconnaissance, Weaponization, Delivery, Exploitation, Installation, Command & Control, Actions on
Objectives.
2. Detect malicious file deployment patterns
3. Infer causality between the current and previous
window based on behavioral continuity...
4. Analyze invocation relationships between entities.
5. Explicitly include the names of the relevant entities.
6. ...
Processing Rules: 1. Strictly preserve the original
temporal order.
2. Merge operations with the same attack intent into
a single phase.
3. Separate different attack vectors into independent
phases.
4. Merge multiple actions triggered by the same entity.
5. 5.evidence_set must fully retain the original log entries.
6. Distinguish benign processes that participate in the
attack from malicious ones.
7. ...
Output Format: Return the result as a JSON array...
