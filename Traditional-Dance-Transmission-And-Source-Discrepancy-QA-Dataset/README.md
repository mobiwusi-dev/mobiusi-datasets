---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Traditional Dance Transmission and Source Discrepancy QA Dataset
---

# Traditional Dance Transmission and Source Discrepancy QA Dataset

This dataset provides closed-domain question-answer examples about traditional dance transmission, historical change, and differences in how sources describe these subjects. Records include source materials, source-by-source comparisons, traceable evidence, applicable scope, answer status, and uncertainty notes, including cases that require qualified conclusions or acknowledgment of conflicting or insufficient evidence. It supports domain-specific supervised fine-tuning and evaluation of source-grounded, cautious responses to traditional dance questions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Traceable excerpts or source locations that support, qualify, or contradict the answer. |
| question | string | A closed-domain question about traditional dance transmission, history, or variations across sources. |
| answer_text | string | A concise response that addresses the question and distinguishes source claims from established facts. |
| answer_status | string | The evidence-based status of the answer, including any required qualifications or findings of insufficient or conflicting evidence. |
| applicable_scope | string | The limits of the answer, such as the tradition, locality, period, community, or record type covered by the cited evidence. |
| source_materials | array | Input source records, with identifiers and sufficient bibliographic or location details to trace each excerpt. |
| uncertainty_note | string | An explanation of unresolved ambiguity, source disagreement, missing context, or why the evidence does not support a stronger conclusion. |
| source_comparison | array | A source-by-source summary of relevant claims and differences, keeping distinct accounts separate. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

