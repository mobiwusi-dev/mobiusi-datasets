---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: License Fee and Audit Clause Retrieval Dataset
---

# License Fee and Audit Clause Retrieval Dataset

This dataset focuses on payment and accounting provisions in licensing agreements, including royalties, minimum guarantees, advances, settlement cycles, sales reports, audit rights, tax obligations, and late payments. It pairs natural-language queries with candidate contract evidence and provides clause categories, normalized terms, obligation lists, key quotations, retrieval answers, audit-right labels, and extraction confidence to support the evaluation and improvement of legal RAG systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | A natural-language query about payment obligations, accounting duties, or audit rights in a licensing agreement. |
| obligations | array | Specific contractual obligations derived from the evidence excerpt for citation by a retrieval-augmented generation system. |
| evidence_quote | string | A direct quotation from the contract that answers the query, preserving key details such as amounts, rates, deadlines, parties, and conditions where available. |
| clause_category | string | The primary clause category inferred from the retrieval query and evidence content. |
| has_audit_right | boolean | Indicates whether the evidence excerpt grants the licensor or another rights holder the right to audit books, records, or sales data. |
| contract_excerpt | string | An original excerpt from a licensing agreement that may contain evidence relevant to payment or accounting obligations. |
| normalized_terms | object | Payment and accounting terms extracted from the evidence excerpt and organized into a consistent structure. |
| retrieval_answer | string | A concise response to the query based on the contract evidence, identifying the relevant payment or accounting obligations. |
| extraction_confidence | number | Overall confidence in the extracted clause category, normalized information, and obligation list, on a scale from 0 to 1. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

