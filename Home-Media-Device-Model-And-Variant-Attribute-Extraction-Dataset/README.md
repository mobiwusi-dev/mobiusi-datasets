---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Home Media Device Model and Variant Attribute Extraction Dataset
---

# Home Media Device Model and Variant Attribute Extraction Dataset

This dataset focuses on catalog entries for home media servers and players, with product titles, descriptions, and specifications that mention specific models, product series, and configuration variants. Its examples emphasize separating model-level attributes from series-level information and preserving an unavailable status when the catalog does not provide clear evidence, helping reduce attribute misattribution. It supports structured-output fine-tuning, catalog attribute extraction, and model information validation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| product_series | string | The product family or series named in the listing, kept separate from the specific model or variant. Use an empty string if not stated. |
| device_category | string | The most specific home media device category supported by the listing. |
| attribute_results | array | Per-attribute extraction results. Include relevant attributes even when the catalog does not provide them, using the not_provided status in that case. Do not treat series-level information as model-specific unless the listing makes that association explicit. |
| catalog_entry_text | string | The original product title, description, and specifications as provided in the catalog. Preserve the source wording for downstream extraction. |
| model_match_status | string | Indicates whether the listing provides enough evidence to associate the extracted attributes with a specific model or variant. |
| variant_configuration | string | The configuration that distinguishes this listing from related models or variants, such as storage size, included tuner, or regional version. Use an empty string if not stated. |
| identified_model_number | string | The exact model number explicitly associated with the listed item. Use an empty string if the listing does not identify it clearly. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

