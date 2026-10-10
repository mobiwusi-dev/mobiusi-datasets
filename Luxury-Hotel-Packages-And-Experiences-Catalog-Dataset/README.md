---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Luxury Hotel Packages and Experiences Catalog Dataset
---

# Luxury Hotel Packages and Experiences Catalog Dataset

This dataset contains catalog descriptions of luxury hotel packages, resort experiences, and bundled services, with structured attributes covering package components, applicable dates and guest types, duration, service locations, included benefits, and restrictions. It spans varied hotel product descriptions and service details, supporting model training to interpret bundled offerings and extract information into defined fields. It is suited to structured output SFT, hotel catalog parsing, product information organization, and related intelligent applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| duration | string | The stated duration of the package or experience, preserving the original units or time range. |
| package_name | string | The stated name of the package, experience, or bundled service in the catalog entry. |
| restrictions | array | Booking, usage, cancellation, redemption, age, or other restrictions that apply to the package. |
| eligible_guests | array | The guest types or eligibility conditions for the package, such as adults, children, hotel guests, or members. |
| applicable_dates | array | The dates, date ranges, days of the week, or seasons when the package applies; leave blank if not stated. |
| included_benefits | array | Benefits, facility access, dining, or other services explicitly included in the package price or experience. |
| service_locations | array | The hotel areas, venues, or specific locations where package items or experiences are provided. |
| package_components | array | The main items, activities, or bundled services included in the package or experience. |
| source_description | string | The original text of the hotel package or experience catalog entry. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

