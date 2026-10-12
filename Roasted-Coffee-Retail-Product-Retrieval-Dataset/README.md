---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Roasted Coffee Retail Product Retrieval Dataset
---

# Roasted Coffee Retail Product Retrieval Dataset

This dataset contains retail catalog entries for roasted coffee products sold to consumers, paired with natural-language queries. Product information covers attributes such as brand, origin, blend, roast level, bean form, and package size, while each record can include a relevance score, matched attributes, and a rationale. It supports training and evaluation of product search, knowledge retrieval, document retrieval, and query-document matching systems for roasted coffee retail.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| user_query | string | A natural-language query submitted by a consumer to retrieve matching coffee products. |
| product_entry | object | A roasted coffee product offered for sale to consumers, together with its catalog attributes. |
| relevance_score | integer | A graded measure of the match between the query and product catalog entry: 0 means irrelevant, 1 means weakly relevant, 2 means relevant, and 3 means highly relevant. |
| matched_attributes | array | Attribute names identified in the product catalog entry as relevant to the query, such as brand, origin, or roast level. |
| matching_rationale | string | An explanation of the main reasons the query matches or does not match the product entry. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

