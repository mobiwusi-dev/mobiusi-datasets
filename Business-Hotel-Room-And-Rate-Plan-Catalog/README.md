---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Business Hotel Room and Rate Plan Catalog
---

# Business Hotel Room and Rate Plan Catalog

This catalog organizes business hotel room types, maximum occupancy, bed configurations, included services, and associated rate plans. Records can include prices, currencies, pricing bases, cancellation policies, and payment terms, linked to source details, quoted evidence, and locators for verification. It supports hotel catalog retrieval systems and the training and evaluation of retrieval-augmented generation models that retrieve and cite relevant evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| currency | string | The currency code or currency name used for the price. |
| bed_types | array | The types and arrangement of beds in the room, such as one king bed or two twin beds. |
| room_type | string | The room category or room name specified in the catalog. |
| hotel_name | string | The name of the hotel associated with the catalog entry. |
| price_basis | string | The unit to which the price applies, such as per room per night or per person per night. |
| price_amount | number | The numeric amount associated with the rate plan. |
| max_occupancy | integer | The maximum number of guests permitted in the room. |
| payment_terms | string | The payment timing, method, or prepayment requirements associated with the rate plan. |
| evidence_quote | string | A verbatim excerpt from the source that supports room or rate fields and enables retrieval and verification. |
| rate_plan_name | string | The price option or rate plan name specified in the catalog. |
| evidence_locator | string | Information identifying where the evidence appears in the source, such as a page section, table row, or page number. |
| included_services | array | Services and amenities explicitly included with the room or rate plan. |
| raw_catalog_source | object | The original source used to extract catalog entry information and its basic metadata. |
| cancellation_policy | string | The cancellation, change, or refund conditions applicable to the rate plan. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

