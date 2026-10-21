---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Near-Duplicate Childrenswear Product Retrieval Disambiguation Benchmark
---

# Near-Duplicate Childrenswear Product Retrieval Disambiguation Benchmark

This benchmark contains childrenswear product documents with similar styles or descriptions but differences in key catalog attributes such as color, size, and material, alongside queries designed to identify those differences. Each record provides a candidate product, a relevance label, distinguishing attributes, and a match rationale, enabling evaluation of query-document matching models on easily confused products. It supports childrenswear catalog search, product-matching model development, and retrieval quality evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | The original user query for childrenswear products, which may specify requirements such as color, size, material, or style. |
| match_reason | string | A brief explanation of whether the candidate product meets the query requirements, including the key attribute differences or evidence for the match. |
| relevance_label | string | The standard match label assigned according to whether the candidate product's key attributes align with the query intent. |
| product_document | object | The original catalog document for a candidate childrenswear product, including its description and key attributes used to distinguish similar products. |
| distinguishing_attributes | array | The key catalog attributes that determine whether the query and candidate product match, such as color, size, or material. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

