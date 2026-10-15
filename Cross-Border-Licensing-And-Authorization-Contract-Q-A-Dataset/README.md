---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cross-Border Licensing and Authorization Contract Q&A Dataset
---

# Cross-Border Licensing and Authorization Contract Q&A Dataset

This dataset covers specialized questions about cross-border licensing and authorization agreements, including licensed territories, export restrictions, governing law, dispute resolution, tax allocation, currencies and payments, sanctions compliance, and language precedence. Records include normalized questions and answers, contractual scope, cited evidence clauses, issue categories, compliance flags, legal-review indicators, and answer confidence to make answers traceable to their contractual basis. It supports training and evaluating models on contract-bounded legal Q&A and on identifying issues that warrant further legal review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer generated or curated within the limits of the contract; it should not go beyond the clauses and their explicit provisions. |
| evidence | array | Excerpts from contract clauses and citation details that support the normalized answer. |
| question | string | A cleaned and normalized question about cross-border licensing and authorization contracts. |
| raw_qa_record | object | An unnormalized source record of questions and answers about cross-border licensing contracts. |
| compliance_flags | array | Cross-border transaction compliance considerations identified from the question and contractual terms. |
| issue_categories | array | Topic labels for issues raised in questions about cross-border licensing contracts. |
| answer_confidence | number | Confidence score from 0 to 1 based on the completeness of contract evidence and the match between the question and relevant clauses. |
| contractual_scope | object | Key terms of the licensing transaction extracted from the contract context. |
| needs_legal_review | boolean | Indicates whether professional legal review is warranted because of ambiguous terms, jurisdictional conflicts, or significant compliance risks. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

