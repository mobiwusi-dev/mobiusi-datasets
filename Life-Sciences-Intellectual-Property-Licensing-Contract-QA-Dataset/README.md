---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Life Sciences Intellectual Property Licensing Contract QA Dataset
---

# Life Sciences Intellectual Property Licensing Contract QA Dataset

This dataset contains closed-domain question-answer pairs grounded in intellectual property licensing contracts for biotechnology, drug development, and diagnostic technologies. Topics include indications and licensed fields, development and registration responsibilities, milestones, sales royalties, patent maintenance, data use, and commercialization rights. Records include contract text, questions, expert answers, and supporting clauses, with structured information on licensing scope, responsibilities, and commercial terms for legal AI training, clause analysis, and transaction review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate, complete, and professionally written response to the question based on the contract text. |
| question | string | A specific question about indications, licensed fields, development and registration responsibilities, milestones, sales royalties, patent maintenance, data use, or commercialization rights. |
| contract_text | string | The full text of the intellectual property licensing contract, or the relevant contract clauses used as the basis for question answering. |
| license_scope | object | Indications, technical fields, territorial scope, exclusivity, and authorized rights extracted from the contract. |
| commercial_terms | object | Economic arrangements covering sales royalties, license fees, milestone payments, payment bases, and sales reporting. |
| evidence_clauses | array | Contract clauses, sections, or excerpts that support the answer. |
| answer_confidence | number | A confidence score from 0 to 1 based on the completeness of contract evidence, clarity of the clauses, and alignment between the question and its supporting evidence. |
| question_category | string | A standardized category for the licensing contract topic addressed by the question. |
| patent_and_data_rights | object | Rights and obligations concerning patent filing and maintenance, patent costs, use of development data, commercialization, and sublicensing. |
| development_and_registration_responsibilities | object | The parties' responsibilities and related costs for development, clinical trials, regulatory submissions, and registration approvals. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

