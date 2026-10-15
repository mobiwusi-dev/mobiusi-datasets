---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Assignment and Subletting Clause Retrieval Dataset
---

# Lease Assignment and Subletting Clause Retrieval Dataset

This dataset focuses on lease provisions concerning assignment of tenant interests, subletting, landlord consent, transferee obligations, and changes in control, paired with factual, conditional, and mixed retrieval queries. It provides structured analyses of transaction scope, contractual restrictions, transferee obligations, and changes in control, along with evidence spans supporting retrieval conclusions. It is designed for building and evaluating legal RAG retrieval systems and supporting contract review, lease transaction analysis, and legal knowledge services.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_type | string | Classifies the retrieval query as factual, conditional, or mixed based on its content. |
| clause_text | string | Original lease clause text related to assignment of tenant interests, subletting, landlord consent, transferee obligations, or changes in control. |
| evidence_spans | array | Key text spans located and annotated in the contract clause to support the retrieval conclusion. |
| retrieval_query | string | A factual or conditional retrieval question about a contract clause. |
| retrieval_result | object | A matching assessment, conditional analysis, and supporting rationale based on the retrieval query and contract clause. |
| transaction_scope | array | Identifies the types of lease transaction arrangements addressed by the clause and query. |
| restriction_analysis | object | Structured analysis of restrictions on assignment, subletting, and landlord consent requirements. |
| transferee_obligations | array | Obligations that the transferee or party succeeding to lease interests must assume under the clause. |
| control_change_analysis | object | Analysis of whether a change in the tenant's ownership, control, or operational control triggers lease restrictions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

