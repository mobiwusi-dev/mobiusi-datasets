---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Small Appliance Product Discovery and Retrieval Dataset
---

# Small Appliance Product Discovery and Retrieval Dataset

This dataset pairs consumer queries about small appliance purchases, including intended use, capacity, features, dimensions, and budget, with retail product pages, product details, and query–product relevance labels. It also provides structured query requirements and product attributes, supporting key steps from understanding shopper needs and extracting product information to judging relevance. Typical uses include training and evaluating document retrieval and query–document matching models, as well as retail knowledge search, product search, semantic retrieval, and retrieval system evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_relevant | boolean | A binary relevance judgment derived from the relevance label. |
| product_brand | string | The brand name extracted from the product page. |
| product_price | number | The product price extracted from the product page and normalized as a numeric value. |
| product_title | string | The product name or page title extracted from the product page. |
| consumer_query | string | The original small appliance purchase request, expressed in terms such as intended use, capacity, features, dimensions, or budget. |
| relevance_label | integer | The query-to-product relevance grade provided by the dataset or assigned by annotators; interpret its numeric value according to the dataset annotation guidelines. |
| normalized_query | string | The consumer query after cleaning and normalization, with its original intent preserved. |
| product_category | string | The small appliance category or subcategory identified from the product page. |
| product_currency | string | The currency code or currency name associated with the product price. |
| product_depth_cm | number | The product depth extracted from the page specifications and converted to centimeters. |
| product_features | array | A list of functions, specifications, selling points, or other product features extracted from the page. |
| product_width_cm | number | The product width extracted from the page specifications and converted to centimeters. |
| query_max_budget | number | The maximum budget amount parsed from the query. |
| matching_evidence | array | A list of text snippets from the product page that support the relevance judgment. |
| product_height_cm | number | The product height extracted from the page specifications and converted to centimeters. |
| product_page_html | string | Raw HTML from a small appliance retail page containing product details, specifications, prices, and related information. |
| product_page_text | string | Product detail text extracted from the original page and cleaned for use. |
| query_intended_use | string | The intended use or usage scenario identified from the consumer query. |
| query_max_depth_cm | number | The maximum depth requirement parsed from the query and converted to centimeters. |
| query_max_width_cm | number | The maximum width requirement parsed from the query and converted to centimeters. |
| product_description | string | A description organized from the product page, covering its intended use, features, and suitable scenarios. |
| query_max_height_cm | number | The maximum height requirement parsed from the query and converted to centimeters. |
| query_budget_currency | string | The currency code or currency name used for the budget in the query. |
| product_capacity_liters | number | The product capacity extracted from the page specifications and converted to liters. |
| query_required_functions | array | A list of target functions or performance requirements identified in the query. |
| matched_query_constraints | array | A list of consumer requirements that match information found in the product details. |
| unmatched_query_constraints | array | A list of consumer requirements that the product does not meet or that cannot be verified from the page. |
| query_required_capacity_liters | number | The capacity requirement parsed from the query and converted to liters. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

