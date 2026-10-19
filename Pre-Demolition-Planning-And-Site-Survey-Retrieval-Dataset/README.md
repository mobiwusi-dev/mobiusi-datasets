---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pre-Demolition Planning and Site Survey Retrieval Dataset
---

# Pre-Demolition Planning and Site Survey Retrieval Dataset

This dataset brings together web-based knowledge about pre-demolition surveys, site risk assessments, work planning, and safety preparation, with evidence passages linked to planning steps and risk-control questions. Coverage varies by source webpage. It supports training and evaluating RAG systems that retrieve knowledge for demolition preparation and helps assess whether answers are grounded in source evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| planning_steps | array | Planning and preparation steps identified in the source, with references to supporting evidence. |
| retrieval_items | array | Questions and expected answers for evaluating retrieval of pre-demolition planning and risk-control knowledge. |
| source_document | object | The original webpage source used to create this record. |
| document_summary | string | A concise summary of source content relevant to pre-demolition preparation. |
| evidence_passages | array | Verbatim or minimally normalized source passages supporting planning steps and risk-control annotations. |
| risk_control_items | array | Site hazards, risk assessment questions, and control measures identified in the source. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

