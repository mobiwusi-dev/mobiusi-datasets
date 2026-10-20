---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Designer and Premium Fashion Product Retrieval Dataset
---

# Designer and Premium Fashion Product Retrieval Dataset

Designed for designer and premium fashion retail, this dataset pairs product catalog records with natural-language product queries and query-product relevance annotations. Search documents bring together product names, designers, categories, descriptions, and available attributes to support consistent product indexing. The data can be used to train and evaluate product-query matching, relevance ranking, and catalog retrieval systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| user_query | string | The original natural-language request used to search for a matching fashion product. |
| relevance_grade | integer | The original relevance annotation for this query-product pair, using the dataset's grading convention. |
| search_document_text | string | A derived text representation that combines the product's catalog name, designer, category, description, and available attributes for retrieval indexing. |
| product_catalog_record | object | The original structured catalog entry for the designer fashion product being evaluated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

