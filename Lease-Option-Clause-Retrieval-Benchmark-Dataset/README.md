---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Option Clause Retrieval Benchmark Dataset
---

# Lease Option Clause Retrieval Benchmark Dataset

This benchmark focuses on five easily confused rights in lease agreements: renewal options, purchase options, expansion rights, rights of first tenancy, and rights of first refusal to purchase. Samples include retrieval queries, contract context, target clauses, and highly similar distractor clauses, alongside annotations for right-related semantic features, candidate comparisons, distractor strength, and retrieval difficulty. The data supports evaluation and improvement of legal RAG systems on fine-grained contractual right retrieval and discrimination.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The original query, right type, contract context, target clause, and distractor clauses for a retrieval benchmark sample. |
| evaluation_focus | array | The lease-right discrimination capabilities that this sample is designed to evaluate. |
| hard_negative_score | number | A score from 0 to 1 measuring distractor strength based on lexical similarity, contract context similarity, and how subtle the difference in rights is. |
| query_right_features | object | Semantic dimensions extracted from the original query and target clause to support fine-grained discrimination among rights. |
| retrieval_difficulty | string | The overall difficulty level of distinguishing fine-grained rights for a retrieval system on this sample. |
| candidate_comparison_annotations | array | Derived annotations produced by consistently distinguishing the target clause from highly similar distractor clauses. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

