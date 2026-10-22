---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Dynamic Travel Packaging Inventory Availability and Pre-Booking Revalidation Code Dataset
---

# Dynamic Travel Packaging Inventory Availability and Pre-Booking Revalidation Code Dataset

This dataset pairs natural-language scenarios with Python code examples covering inventory changes, quote validity, and pre-booking revalidation for flights, hotels, and other supplier products. Structured fields capture product types, inventory status changes, quote timing, revalidation triggers, and checking logic for developing inventory and quote state management in dynamic travel packaging systems. The focus is availability checks and quote updates, not package pricing formulas.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| quote_update_logic | string | Generated or normalized code logic for refreshing or updating supplier quote state without defining package pricing formulas. |
| source_requirement | string | Original natural-language requirement describing availability, inventory, quote validity, or revalidation behavior. |
| source_code_example | string | Reference code example supplied with the requirement, represented as Python source text. |
| revalidation_trigger | string | Condition or event that requires availability or quote revalidation before booking. |
| revalidation_required | boolean | Indicates whether availability or quote details must be checked again before booking. |
| supplier_product_type | string | Normalized category of the supplier product affected by the availability or quote requirement. |
| inventory_status_after | string | Inventory availability status after the described change. |
| quote_expiry_timestamp | string | Timestamp after which the supplier quote is no longer valid, when specified. |
| quote_validity_seconds | integer | Quote validity duration in seconds, when it can be determined from the requirement. |
| inventory_status_before | string | Inventory availability status before the described change. |
| availability_check_logic | string | Generated or normalized code logic for checking current supplier inventory availability. |
| inventory_change_timestamp | string | Timestamp associated with the inventory status change, when specified. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

