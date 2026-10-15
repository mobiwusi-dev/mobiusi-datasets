---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Renewal and Termination Clause Retrieval Dataset
---

# Lease Renewal and Termination Clause Retrieval Dataset

This dataset links natural-language queries to evidence clauses in lease agreements, focusing on renewal options, automatic renewal, early termination, termination conditions, notice periods, and post-termination obligations. Its fields cover queries, contract text, query intent, evidence clauses, structured contractual facts, and evidence-based answer summaries, supporting more accurate and traceable retrieval for lease-related questions. It is suitable for developing legal RAG systems, evaluating clause retrieval, and extracting contractual information.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | A natural-language query about lease renewal or termination. |
| query_intent | object | The lease renewal or termination issue and focus inferred from the user's query. |
| answerability | string | A judgment of whether the retrieved evidence allows the contract text to answer the query fully. |
| contract_text | string | The full lease agreement or relevant clause text used for retrieval and analysis. |
| answer_summary | string | A concise response based on the evidence clauses that does not go beyond what the contract text supports. |
| extracted_terms | array | Key terms extracted from the query and relevant evidence clauses for retrieval, indexing, and recall. |
| evidence_clauses | array | Original contract clauses retrieved as relevant to the query, with location information. |
| contractual_facts | object | Structured facts about renewal and termination extracted from the contract evidence clauses. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

