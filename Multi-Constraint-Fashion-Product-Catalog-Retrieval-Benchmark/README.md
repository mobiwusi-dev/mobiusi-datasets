---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Constraint Fashion Product Catalog Retrieval Benchmark
---

# Multi-Constraint Fashion Product Catalog Retrieval Benchmark

This benchmark targets complex retrieval needs in designer and premium fashion retail catalogs. It pairs natural-language queries containing one or more constraints, such as category, material, silhouette, color, or use occasion, with catalog products for evaluation. Structured query constraints, constraint-match summaries, relevance grades, and supporting explanations make it suitable for assessing query understanding, product retrieval, query-document matching, and relevance ranking; the total record count is not specified in the available information.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | The original natural-language query, which may specify one or more fashion product constraints. |
| catalog_product | object | The catalog product record evaluated for relevance to the query. |
| relevance_grade | integer | An ordinal relevance judgment: 0 means not relevant, 1 weakly relevant, 2 partially relevant, and 3 highly relevant. |
| relevance_reason | string | An explanation for the relevance grade, based on the query constraints and product attributes. |
| query_constraints | object | Structured constraints extracted from the original query to support analysis and product matching. |
| matched_constraints | string | A concise summary of the query constraints satisfied or contradicted by the product. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

