---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial and Industrial Solar Grid-Connection Rules Reasoning Q&A Dataset
---

# Commercial and Industrial Solar Grid-Connection Rules Reasoning Q&A Dataset

Designed for commercial and industrial solar grid-connection reviews, the dataset pairs explicit interconnection rules and project parameters with review questions, compliance judgments, and reasoning explanations. It covers rule application, condition-conflict detection, and identification of missing key information, making it suitable for reasoning SFT, training, and evaluation; the actual sample count and coverage should be confirmed against the dataset.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | Explains the logical relationship between the applicable rules, project parameters, and the assessment. |
| rule_text | string | Explicit grid-connection rules, provisions, or conditions used for the review. |
| answer_text | string | A concise response for the questioner, including the conclusion and any necessary review caveats. |
| user_question | string | A question about applying the rules, identifying conflicts, or determining what additional information is needed. |
| compliance_status | string | Overall assessment based on the rules and the project parameters provided. |
| project_parameters | object | Basic attributes and grid-connection proposal parameters for the solar project under review; unspecified attributes may be omitted. |
| condition_conflicts | array | Conditions in the project proposal that conflict with the rules or contradict one another; an empty array indicates no identified conflicts. |
| missing_information | array | Project parameters or documents still needed for a reliable assessment; an empty array indicates that no additional information is identified as necessary. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

