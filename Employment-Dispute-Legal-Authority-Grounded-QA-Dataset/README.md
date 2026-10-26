---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Dispute Legal Authority Grounded QA Dataset
---

# Employment Dispute Legal Authority Grounded QA Dataset

This dataset addresses common employment dispute topics, including employment relationship status, wages, working hours, leave, contract termination, and compensation, with answers framed for a specified jurisdiction and reference date. Each record includes the legal materials available for answering, a direct response, a concise analysis, specific legal citations, and an answer status, making the basis and applicable version traceable. It supports domain fine-tuning, closed-domain evaluation, and testing of legal grounding in employment law question-answering systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct response limited to conclusions supported by the provided legal materials. |
| question | string | The employment dispute question to be answered. |
| citations | array | Specific legal authorities supporting the answer, linked to the provided materials and reference date. |
| jurisdiction | string | The jurisdiction whose employment laws and regulations govern the answer. |
| answer_status | string | Whether the provided legal materials support a definitive answer or are insufficient to resolve the question. |
| reference_date | string | The date used to determine which legal provisions and versions apply. |
| legal_materials | array | The closed set of legal materials available for answering the question, including relevant provision text and version or effective period. |
| analysis_summary | string | A concise explanation of how applicable provisions support the answer, including relevant conditions or distinctions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

