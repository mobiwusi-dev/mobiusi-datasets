---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Agreement Clause Retrieval Dataset
---

# Employment Agreement Clause Retrieval Dataset

This dataset includes full employment agreements, clause-level segments, legal and business queries, and annotations for relevant clauses and supporting evidence. Its coverage includes common topics such as job duties, contract terms, compensation and benefits, confidentiality, and termination. Query intents, clause relevance, and evidence spans support the development and evaluation of RAG systems that retrieve supporting provisions from contract text, as well as legal document question answering and HR compliance workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| user_query | string | A legal or business question about an employment agreement. |
| query_intent | string | The contract topic inferred from the user query, such as job duties, contract term, compensation and benefits, confidentiality obligations, termination, working hours, or dispute resolution. |
| contract_text | string | The original employment agreement text to be searched, serving as the source for clause segmentation and evidence localization. |
| evidence_spans | array | Text extracted from relevant clauses and annotated as direct evidence supporting an answer to the query. |
| clause_segments | array | Clause-level text segmented from the full contract, with its location in the source text. |
| relevant_clauses | array | Clauses directly related to the user query and their relevance annotations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

