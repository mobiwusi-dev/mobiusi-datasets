---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Individual Medical Expense Insurance Coverage Question-Answer Dataset
---

# Individual Medical Expense Insurance Coverage Question-Answer Dataset

This dataset organizes questions and answers about covered medical services, coverage conditions, expense limits, and benefits under individual medical expense insurance policies and coverage descriptions. Each item links a question with the relevant policy clause, an answer, a coverage status, applicable conditions, and supporting evidence, enabling answers to be retrieved and checked against the source wording. It supports the development and evaluation of retrieval-augmented generation systems for accurate, traceable insurance coverage Q&A, as well as policy search and customer-facing assistance.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A clear answer grounded in the provided source policy clause. |
| question | string | A question about covered medical services, coverage conditions, or benefit amounts. |
| source_clause | string | The original policy wording relevant to answering the question. |
| evidence_quote | string | An exact or minimally excerpted quotation from the source clause that supports the answer. |
| coverage_status | string | Whether the clause indicates that the service or expense is covered, excluded, conditional, or unclear. |
| coverage_conditions | array | Conditions, limits, or requirements applicable to the described coverage. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

