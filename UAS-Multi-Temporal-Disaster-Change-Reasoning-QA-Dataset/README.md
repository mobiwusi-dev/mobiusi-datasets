---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: UAS Multi-Temporal Disaster Change Reasoning QA Dataset
---

# UAS Multi-Temporal Disaster Change Reasoning QA Dataset

This dataset presents pre- and post-disaster UAS mapping observations as question-answer examples, with explicit rules for distinguishing newly observed changes, pre-existing damage, and cases where evidence is insufficient. Each example includes a question, answer, change classification, reasoning, and evidence summary, supporting reasoning SFT and disaster change attribution evaluation while helping reduce false attribution of existing conditions as new damage. The dataset size is not specified in the available information.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | The question to answer by comparing the pre- and post-disaster survey records and applying the inference rules. |
| reasoning | string | A brief explanation of how the pre- and post-disaster records and stated rules support the classification. |
| answer_text | string | A concise natural-language answer grounded in the temporal survey evidence and inference rules. |
| inference_rules | string | Explicit rules for distinguishing newly observed changes, pre-existing damage, and cases where the evidence is insufficient. |
| evidence_summary | string | A concise summary of the observations supporting the conclusion, including relevant temporal comparisons or missing evidence. |
| pre_disaster_survey | string | Textualized UAS mapping observations recorded before the disaster, including any damage or conditions already present. |
| post_disaster_survey | string | Textualized UAS mapping observations recorded after the disaster. |
| change_classification | string | The inferred temporal status of the relevant condition. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

