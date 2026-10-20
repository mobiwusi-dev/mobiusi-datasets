---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Battery Management System Protection Logic Code Verification Dataset
---

# Battery Management System Protection Logic Code Verification Dataset

This dataset contains source code samples from battery management system (BMS) firmware covering overvoltage, undervoltage, overcurrent, and temperature protection. Annotations indicate whether protection conditions are satisfied and identify defect root causes, faulty branches, and boundary-condition behavior. It supports model training and evaluation for protection logic verification, defect localization, threshold analysis, and explanation of verification results. Typical uses include battery control firmware development, embedded software testing, and code review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | A BMS firmware source code sample containing overvoltage, undervoltage, overcurrent, or temperature protection logic. |
| faulty_branch | string | The conditional branch or decision path responsible for an identified protection logic defect, or an empty string when no faulty branch exists. |
| defect_root_cause | string | The root cause of a protection logic defect, or an empty string when no defect is identified. |
| protection_category | string | The protection function addressed by the code, such as overvoltage, undervoltage, overcurrent, or temperature protection. |
| verification_rationale | string | A concise explanation supporting the protection-condition result and defect analysis. |
| boundary_condition_description | string | A description of relevant threshold, comparison, or boundary-condition behavior identified during verification. |
| protection_condition_satisfied | boolean | Indicates whether the source code correctly satisfies the required protection condition. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

