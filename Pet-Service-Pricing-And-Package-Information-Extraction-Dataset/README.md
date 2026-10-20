---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pet Service Pricing and Package Information Extraction Dataset
---

# Pet Service Pricing and Package Information Extraction Dataset

This dataset contains text and structured annotations from pet service webpages, covering service names and categories, prices, billing units, package contents, and additional fees across services such as bathing, grooming, boarding, and veterinary care. It preserves original price wording and provides fields for price ranges, pricing models, and conditions that affect costs, helping models extract and organize comparable service information. It supports pet service search, price comparison, and task-specific fine-tuning for pet service discovery.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| currency | string | The currency used for the price, such as CNY or yuan. |
| price_max | number | The maximum numeric price extracted from the price wording; leave blank if no identifiable maximum is available. |
| price_min | number | The minimum numeric price extracted from the price wording; leave blank if no identifiable minimum is available. |
| price_text | string | The original price wording from the webpage, including starting prices, price ranges, or discount details. |
| source_text | string | Raw text from a pet service webpage containing pricing and package details. |
| billing_unit | string | The unit to which the price applies, such as per visit, per hour, per night, or per pet. |
| package_name | string | The name of a service package or priced item explicitly mentioned on the webpage. |
| service_name | string | The pet service name extracted from the original webpage text. |
| pricing_model | string | A normalized summary of the pricing method. |
| additional_fees | array | Extra charges mentioned beyond the package or service price. |
| package_contents | array | A list of services or benefits included in the package. |
| price_conditions | string | Conditions that may affect the price, such as pet size, breed, service duration, or holidays. |
| service_category | string | The category of the service, such as bathing, grooming, boarding, or veterinary care. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

