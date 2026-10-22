---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Menu Attribute Extraction Dataset for Casual Dining Items
---

# Menu Attribute Extraction Dataset for Casual Dining Items

This dataset uses casual dining menu item names and original descriptions as input, with structured attributes for item category, explicitly listed ingredients, cooking methods, portion information, and price information. It covers item details supported by the menu text and uses empty values when an attribute is not stated or cannot be reliably determined, making it suitable for training and evaluating menu understanding and structured information extraction.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| price | object | Price information explicitly stated in the menu text; use null when no price is stated. |
| portion | object | Portion or serving information explicitly stated in the menu text; use null when none is stated. |
| category | object | A broad category for the item, supported by the menu name or description; use null when the text does not support a reliable category. |
| item_name | string | The original menu item name provided as input. |
| ingredients | array | Ingredients explicitly named in the item name or description. Do not infer unstated ingredients; use an empty array when none are listed. |
| cooking_methods | array | Cooking methods explicitly stated in the item name or description. Do not infer unstated methods; use an empty array when none are stated. |
| item_description | string | The original menu item description provided as input. Preserve the source wording. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

