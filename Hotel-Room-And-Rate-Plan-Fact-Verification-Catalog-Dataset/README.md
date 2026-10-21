---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Hotel Room and Rate Plan Fact Verification Catalog Dataset
---

# Hotel Room and Rate Plan Fact Verification Catalog Dataset

This dataset organizes catalog records for hotel room types and rate plans, covering hotel names, room types, bed configurations, maximum occupancy, meal inclusions, cancellation rules, and applicable conditions. Each factual claim is linked to the relevant catalog attribute, claimed value, recorded catalog value, and verification outcome, supporting model training and evaluation for evidence-based validation of lodging product information. It is suited to catalog verification workflows in travel pricing, lodging information management, and revenue management.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| hotel_name | string | Name of the hotel associated with the catalog entry. |
| catalog_value | string | Value recorded in the catalog for the attribute being verified. |
| claimed_value | string | Value asserted by the factual claim for the identified attribute. |
| meal_inclusion | string | Meal or board arrangement included in the rate plan. |
| rate_plan_name | string | Catalog name of the rate plan associated with the room. |
| room_type_name | string | Catalog name of the room type. |
| claim_attribute | string | Catalog attribute that the factual claim concerns. |
| bed_configuration | object | Bed types and quantities provided in the room. |
| cancellation_rule | object | Cancellation terms associated with the rate plan. |
| fact_claim_source | string | Original statement asserting a fact about a hotel room or rate plan. |
| maximum_occupancy | integer | Maximum number of guests permitted in the room. |
| verification_result | string | Outcome of comparing the factual claim with the catalog record. |
| applicable_conditions | array | Conditions or restrictions governing the room or rate plan, such as stay dates, guest eligibility, or minimum stay requirements. |
| catalog_record_source | string | Original catalog text or other source content describing the hotel room and rate plan. |
| verification_explanation | string | Brief explanation of the verification outcome, including relevant catalog evidence or missing information. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

