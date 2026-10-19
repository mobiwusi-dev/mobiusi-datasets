---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Menswear Fit and Size Query Matching Dataset
---

# Menswear Fit and Size Query Matching Dataset

This dataset pairs user queries containing menswear fit or size expressions, such as slim, regular, relaxed, or long, with catalog entries that provide fit descriptions, size information, or size charts. It includes the original query and catalog text, fit and size expressions, match relations, and explanations. The annotations support training and evaluation for e-commerce query-to-product matching, attribute understanding, and relation classification.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | The original user query about fit, size, or a related product. |
| match_relation | string | The labeled relationship between the user's query expressions and the product catalog information. |
| match_explanation | string | A brief explanation of the matching decision, including the fit and size dimensions that match or do not match. |
| catalog_entry_text | string | The original catalog entry containing menswear fit details, size information, or a size chart. |
| query_fit_expression | string | The fit expression extracted from the user query, such as slim, regular, relaxed, or long. An empty string is used if no fit expression is mentioned. |
| query_size_expression | string | The size or measurement expression extracted from the user query. An empty string is used if none is mentioned. |
| catalog_fit_expression | string | The fit expression extracted from the product catalog entry. An empty string is used if no fit expression is provided. |
| catalog_size_information | string | Size descriptions, size chart content, or related measurements extracted from the product catalog entry. An empty string is used if no size information is provided. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

