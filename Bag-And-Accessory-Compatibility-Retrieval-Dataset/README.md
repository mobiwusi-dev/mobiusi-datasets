---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Bag and Accessory Compatibility Retrieval Dataset
---

# Bag and Accessory Compatibility Retrieval Dataset

This dataset contains product catalog entries for bags, shoulder straps, wallets, bag charms, and related items, along with compatibility, fit, or pairing relationships between products. Each retrieval example includes a query based on an existing bag or accessory, target-product match annotations, eligible product codes, and a compatibility summary. It supports training and evaluating retail product relationship models, compatible-item retrieval systems, and query-to-product matching.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| match_count | integer | Number of target products labeled as exact matches or compatible items. |
| catalog_items | array | Catalog records for bags, shoulder straps, wallets, bag charms, and other products involved in compatibility retrieval. |
| target_matches | array | The target products for a query and their annotated match relevance. |
| retrieval_query | object | Search criteria based on an existing bag or accessory. |
| compatibility_summary | string | A brief fit or compatibility explanation generated from the query anchor, product relationships, and catalog. |
| eligible_product_codes | array | Product codes derived from the query anchor product and compatibility relationships. |
| compatibility_relations | array | Records of compatibility, fit, or pairing relationships between catalog products. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

