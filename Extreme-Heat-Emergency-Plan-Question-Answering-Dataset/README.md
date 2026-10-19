---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Extreme Heat Emergency Plan Question Answering Dataset
---

# Extreme Heat Emergency Plan Question Answering Dataset

This dataset is based on local or institutional extreme heat emergency plans, response procedures, and descriptions of assigned responsibilities. It organizes question-answer text about response activation criteria, role assignments, and emergency measures, with each record providing the source passage, question, answer, and supporting evidence; structured details such as criteria, responsible parties, measures, and topic may also be included. It is suitable for building and evaluating retrieval-augmented generation systems, emergency management knowledge bases, and information services related to heat risk.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| topic | string | The primary emergency management topic addressed by the question, such as activation, roles, or public protective actions. |
| answer | string | A concise answer to the question, supported by information in the source text. |
| question | string | A question about activation criteria, responsibilities, or response measures that can be answered from the source text. |
| source_text | string | The original plan passage used as the source for generating the question and answer. |
| answer_evidence | string | A supporting quotation or relevant passage from the source text that substantiates the answer. |
| response_measures | array | Actions or protective measures relevant to the question and specified in the plan. |
| activation_criteria | array | Conditions or thresholds specified in the plan for activating an extreme heat response. |
| responsible_parties | array | Agencies, teams, or roles assigned responsibilities relevant to the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

