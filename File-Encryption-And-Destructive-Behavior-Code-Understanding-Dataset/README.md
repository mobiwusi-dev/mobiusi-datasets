---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: File Encryption and Destructive Behavior Code Understanding Dataset
---

# File Encryption and Destructive Behavior Code Understanding Dataset

This dataset contains source code samples involving file traversal, encryption, renaming, deletion, overwriting, and key management, together with behavioral explanations and risk analyses. It helps models distinguish legitimate business encryption logic from implementations that could cause ransomware-like impact, including risk boundary analysis, key security review, and mitigation recommendations. It is designed for code security assessment, model training, and the improvement of security analysis workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The source code under analysis and its basic context, serving as the original input for the record. |
| risk_assessment | object | An overall assessment of whether the code could cause ransomware-like impact, with supporting rationale. |
| boundary_analysis | object | Conditions under which the code represents legitimate functionality and conditions under which it could become a dangerous implementation. |
| operation_analysis | array | A step-by-step account of file traversal, encryption, renaming, deletion, overwriting, and other operations in the code. |
| code_behavior_summary | string | An overview of the code's overall function, main execution flow, and potential impact. |
| key_management_analysis | object | An analysis of key generation, origin, storage, use, and recoverability, including related security risks. |
| mitigation_recommendations | array | Recommendations addressing code risks, key management, access control, backup and recovery, and monitoring and auditing. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

