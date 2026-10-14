---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Non-Disclosure Agreement Clause Interpretation and Obligations QA Dataset
---

# Non-Disclosure Agreement Clause Interpretation and Obligations QA Dataset

This dataset builds closed-domain question-answer pairs from full unilateral and mutual non-disclosure agreements, including definitions and cross-referenced provisions. It covers the scope of confidential information, permitted uses, confidentiality obligations, exceptions, duration, and governing law, with expert answers grounded in the agreement text. Samples may also include evidence excerpts, structured clause interpretations, and links between referenced provisions, supporting long-tail legal knowledge learning, QA evaluation, and domain-specific model training.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate and complete expert response grounded in the agreement text and limited to what the text supports. |
| question | string | A question about agreement content, such as the scope of confidential information, permitted uses, confidentiality obligations, exceptions, duration, or governing law. |
| support_score | number | A numerical score from 0 to 1 that measures the degree of support for the answer in the agreement text. |
| agreement_text | string | Full text of a unilateral or mutual non-disclosure agreement, including definitions and relevant cross-referenced provisions used to answer the question. |
| evidence_quotes | array | Excerpts from the agreement that support the expert answer, with their clause locations and explanations of their relevance. |
| cross_references | array | Relationships between the clauses addressed by the answer and other referenced definitions, obligations, exceptions, or duration provisions in the agreement. |
| question_category | string | A category identifying the non-disclosure agreement topic addressed by the question. |
| answer_is_fully_supported | boolean | Indicates whether the answer's main conclusions are directly supported by the agreement text or by explicit cross-references. |
| structured_interpretation | object | A topic-based structured summary of the key non-disclosure agreement elements addressed in the answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

