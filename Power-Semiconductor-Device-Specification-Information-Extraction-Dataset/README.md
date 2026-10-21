---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Power Semiconductor Device Specification Information Extraction Dataset
---

# Power Semiconductor Device Specification Information Extraction Dataset

This dataset covers manufacturer product-page descriptions of power MOSFETs, IGBTs, and power diodes, with structured information on device type, product and part identifiers, electrical ratings, switching characteristics, thermal parameters, and package details. Examples preserve parameter values, units, test conditions, and source text to help models understand when specifications apply and avoid treating conditional values as universal ratings. It supports specification parsing, information extraction, and structured data processing for power and power-management applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| device_type | string | Power semiconductor device category identified from the product description. |
| part_number | string | Manufacturer part number or device identifier. |
| manufacturer | string | Manufacturer name as stated on the product page. |
| product_name | string | Product name or title as stated on the product page. |
| source_content | string | Original manufacturer product-page content used as the input for extraction. |
| extraction_notes | array | Notes about ambiguity, missing details, or interpretation decisions relevant to the extracted specifications. |
| electrical_ratings | array | Electrical ratings and their limits, values, units, and applicable conditions. |
| thermal_parameters | array | Thermal parameters with their reported values, units, applicable conditions, and supporting source text. |
| package_information | object | Package and mounting details stated for the device. |
| switching_characteristics | array | Switching parameters with their reported values, units, test conditions, and supporting source text. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

