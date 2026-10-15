---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Licensing Agreement Clause Retrieval Dataset
---

# Licensing Agreement Clause Retrieval Dataset

This dataset covers full licensing agreements, hierarchical clauses, legal business questions, and their supporting evidence clauses, including key topics such as grant scope, term, territory, fees, and termination. It includes normalized clauses, retrieval chunks, query intent information, and evidence alignments to support the development and optimization of legal RAG retrieval workflows. Typical uses include legal question answering, contract review assistance, retrieval evaluation, and evidence traceability.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| rag_record | object | A record for retrieval-augmented generation that brings together the query, context chunks, and evidence scope. |
| source_data | object | Raw inputs for licensing agreement retrieval, including full contract text, clause segmentation, legal questions, and corresponding evidence clauses. |
| query_profile | object | Normalized questions, intent categories, and retrieval targets derived from legal business questions. |
| retrieval_chunks | array | Contract text chunks prepared for RAG retrieval, together with retrieval metadata. |
| evidence_alignment | array | Evidence alignment results matching legal business questions with normalized clauses and retrieval chunks. |
| normalized_clauses | array | Clause records with hierarchical organization, topic categories, and retrieval fields added to the source clauses. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

