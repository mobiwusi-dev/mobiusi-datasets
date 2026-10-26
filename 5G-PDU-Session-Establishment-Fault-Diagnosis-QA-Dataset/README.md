---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G PDU Session Establishment Fault Diagnosis QA Dataset
---

# 5G PDU Session Establishment Fault Diagnosis QA Dataset

This dataset covers 5G core network scenarios involving failed or abnormal PDU session establishment, with question-answer examples featuring clues about DNN, S-NSSAI, SMF, UPF, and policy interactions. It addresses potential causes such as configuration mismatches, network function selection, and network function processing. Evidence mappings, diagnostic reasoning, and recommended validation steps connect case clues to likely causes, supporting reasoning SFT, fault localization training, and diagnostic evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| diagnosis | string | The most likely explanation for the PDU session establishment failure or abnormal behavior. |
| reasoning | string | A concise reasoning trace explaining how the available clues support the diagnosis and distinguish it from alternatives. |
| case_input | string | The original textual question and case clues, including relevant DNN, S-NSSAI, SMF, UPF, and policy interactions. |
| evidence_mapping | string | An explanation linking clues in the case input to the proposed diagnosis. |
| root_cause_category | string | The primary class of suspected issue, such as a configuration mismatch, network function selection, or network function processing. |
| recommended_validation | string | Suggested checks or troubleshooting steps for validating the diagnosis in the 5G core network. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

