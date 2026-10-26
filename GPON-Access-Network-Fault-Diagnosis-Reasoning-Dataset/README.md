---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: GPON Access Network Fault Diagnosis Reasoning Dataset
---

# GPON Access Network Fault Diagnosis Reasoning Dataset

This dataset provides question-and-answer examples for diagnosing GPON access network faults using alarms, equipment operating states, user-reported symptoms, and configuration excerpts. Each example includes concise reasoning, a likely fault, and practical validation steps, helping models connect evidence, weigh supporting or conflicting clues, and recommend checks. It is suited to developing GPON network operations assistants, training fault analysis, and evaluating diagnostic reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | A concise explanation connecting the available evidence to the diagnosis, including relevant supporting or conflicting clues. |
| final_answer | string | A concise response summarizing the likely fault and the most important next verification action. |
| likely_fault | string | The most likely GPON fault or failure condition inferred from the evidence. |
| user_symptoms | string | User-reported symptoms, including affected services and their scope or timing. |
| alarm_evidence | string | Original GPON alarm messages, event codes, timestamps, and related alarm details. |
| validation_steps | array | Ordered, practical checks for confirming or ruling out the likely fault. |
| operational_state | string | Original observations and measurements of OLT, ONU, or service operating states. |
| diagnostic_question | string | The question to answer using the supplied alarm, operating state, symptom, and configuration evidence. |
| configuration_excerpt | string | Relevant GPON configuration snippets or configuration details. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

