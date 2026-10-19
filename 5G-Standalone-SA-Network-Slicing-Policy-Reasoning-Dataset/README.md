---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G Standalone (SA) Network Slicing Policy Reasoning Dataset
---

# 5G Standalone (SA) Network Slicing Policy Reasoning Dataset

This question-answer text dataset represents 5G SA network slicing scenarios involving subscription information, session requirements, slicing policy conditions, and asserted slice selections or policy outcomes. Each example asks the model to assess whether a result follows from the supplied constraints and to provide the expected outcome or explain when the information is insufficient, with a concise rationale. It supports slicing policy validation, telecom logic reasoning, and reasoning-oriented supervised fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | A concise explanation connecting the subscription information, session requirements, and policy conditions to the consistency judgment and corrected result. |
| input_case | string | The source text containing subscription information, session requirements, slicing policy conditions, any asserted slice or policy result, and the question to answer. |
| is_consistent | boolean | Whether the asserted slice selection or policy result is consistent with the supplied constraints. Set to false when the information is insufficient to establish consistency. |
| corrected_result | string | The expected slice selection or policy outcome under the supplied constraints, or a brief statement that it cannot be determined. |
| consistency_label | string | The derived classification indicating whether the asserted slice selection or policy result is consistent with the supplied constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

