---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Portfolio Legal Status and Prosecution History QA Dataset
---

# Patent Portfolio Legal Status and Prosecution History QA Dataset

This dataset focuses on patent application, examination, grant, maintenance, and other legal events within patent portfolios. It provides closed-domain questions and answers about current legal status, event timelines, and supporting record evidence, grounded in the supplied status and prosecution history materials. It supports patent lifecycle management, portfolio analysis, legal status verification, and domain-specific model fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct answer based only on the supplied legal record materials, with relevant evidence references where appropriate. |
| user_question | string | The original question about a patent's current status, lifecycle events, or supporting record evidence. |
| event_timeline | array | Chronological list of relevant application, examination, grant, maintenance, and other legal events supported by the materials. |
| evidence_citations | array | Record references and supporting excerpts that substantiate the answer and any stated status or timeline events. |
| current_legal_status | string | The current legal status stated or supported by the supplied materials, such as pending, granted, expired, or lapsed. |
| legal_record_materials | string | Original legal status, prosecution history, and other patent lifecycle materials supplied as evidence for answering the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

