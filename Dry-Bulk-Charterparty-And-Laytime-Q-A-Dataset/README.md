---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Dry Bulk Charterparty and Laytime Q&A Dataset
---

# Dry Bulk Charterparty and Laytime Q&A Dataset

This dataset contains dry bulk charterparty clauses, related web text, and practical explanations of laytime and demurrage, paired with questions and answers based on the source material. Each record links the source document with a question, an answer, and supporting source evidence, making it easier to trace responses to the relevant clause or explanation. It is designed for retrieval-augmented generation, shipping contract document QA, and knowledge retrieval and evaluation in the dry bulk shipping domain.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer to the question grounded in the source document. |
| evidence | array | Source excerpts supporting the answer and their locations in the material. |
| question | string | A question about chartering, laytime, or demurrage based on the source material. |
| source_document | string | Original contract clauses, web text, or practical explanations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

