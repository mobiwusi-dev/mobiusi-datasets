---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G SA Registration and PDU Session Troubleshooting Reasoning Dataset
---

# 5G SA Registration and PDU Session Troubleshooting Reasoning Dataset

This dataset presents troubleshooting scenarios for UE registration, authentication, and PDU session establishment in 5G Standalone networks, with reported symptoms, control-plane signaling clues, questions, and analyses. Samples guide models to use protocol evidence to identify likely failure stages step by step and explain how the evidence supports or rules out competing hypotheses. It is designed for 5G core network diagnostics, protocol analysis, and reasoning-focused fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| failure_stage | string | The most likely stage of registration, authentication, or PDU session establishment where the failure occurs. |
| reasoning_trace | string | A step-by-step explanation linking signaling clues to the likely point of failure. |
| case_description | string | Background and relevant context for the UE registration or PDU session issue. |
| observed_symptoms | string | User-visible or network-observed symptoms reported for the affected UE. |
| recommended_checks | array | Follow-up checks to confirm the diagnosis or distinguish between plausible causes. |
| signaling_evidence | string | Relevant 5G SA control-plane messages, protocol fields, and signaling clues used for diagnosis. |
| evidence_assessment | string | An interpretation of key evidence and how it supports or weakens possible failure hypotheses. |
| troubleshooting_answer | string | A concise diagnosis and direct response to the troubleshooting question. |
| troubleshooting_question | string | The question to be answered using the provided symptoms and signaling evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

