---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: FTTB Service Provisioning Eligibility Deductive Reasoning Dataset
---

# FTTB Service Provisioning Eligibility Deductive Reasoning Dataset

This question-and-answer text dataset focuses on eligibility decisions for FTTB service provisioning. Each example presents facts such as building coverage, access resources, port occupancy, and provisioning rules, then asks the model to determine whether service can be activated, explain the basis for its conclusion, or identify facts needed to resolve uncertainty. It is designed for reasoning SFT to strengthen rule-based deduction in FTTB provisioning scenarios.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| decision | string | The decision derived from the original scenario and its rules. |
| input_case | string | The original input text containing building coverage status, access resources, port occupancy, provisioning rules, and the question to be decided. |
| reasoning_basis | string | Explains how the known facts and provisioning rules lead to the eligibility decision, or why the available information is insufficient. |
| missing_information | string | When the available information is insufficient to determine the outcome, identifies the additional facts needed; otherwise, contains none. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

