---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Food Nutrition Information Claim Verification Dataset
---

# Food Nutrition Information Claim Verification Dataset

This dataset pairs claims about food product nutrition with corresponding grocery and fresh food delivery catalog records. It covers nutrient names, amounts per serving, and nutrition label information, including cases involving matching values, unit differences, and missing catalog details. Structured fields capture the claim, catalog evidence, comparison results, verdict, and rationale, making the data suitable for training and evaluating fact verification models and for research on automated nutrition claim checking.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | Indicates whether the product catalog record supports the claim. |
| rationale | string | Briefly explains the catalog evidence, amount and unit comparison, and reasoning behind the verification verdict. |
| claim_text | string | The original claim to be verified, concerning product nutrients, amounts per serving, or nutrition label information. |
| claim_unit | string | The unit and applicable serving-size expression associated with the claimed amount. |
| amount_match | boolean | Indicates whether the claimed and catalog amounts agree when their units and serving bases are comparable; left unpopulated when they cannot be compared. |
| catalog_unit | string | The unit and applicable serving-size expression associated with the catalog amount; left unpopulated when the catalog does not provide it. |
| claim_amount | number | The amount extracted from the claim; populated only when the claim specifies a numerical value. |
| unit_relation | string | Indicates whether the claim and catalog units are the same, convertible, incompatible, or not comparable because catalog information is missing. |
| catalog_amount | number | The corresponding nutrient amount extracted from the product catalog record; left unpopulated when the catalog does not provide it. |
| claim_nutrient | string | The name of the nutrient extracted from the claim. |
| product_catalog_record | object | The grocery and fresh food delivery catalog record used to verify the claim, retaining the available product and nutrition information. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

