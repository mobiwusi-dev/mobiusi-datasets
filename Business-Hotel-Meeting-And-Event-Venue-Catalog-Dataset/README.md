---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Business Hotel Meeting and Event Venue Catalog Dataset
---

# Business Hotel Meeting and Event Venue Catalog Dataset

This dataset organizes catalog information for business hotel meeting rooms, ballrooms, and other event venues, including venue types, floor areas, capacities across seating layouts, equipment, venue combinations, and meeting or catering packages. Venue facts can be linked to source text excerpts and their locations, supporting verification and searches based on attendee count, layout, and service requirements. It is designed for hotel venue retrieval, evidence retrieval, and training or evaluation of retrieval-augmented generation systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| area_sqm | number | The usable area of the venue, measured in square meters. |
| equipment | array | A list of meeting and event equipment installed in or available for the venue. |
| hotel_name | string | The name of the hotel that provides the meeting room or event venue. |
| venue_name | string | The name of the meeting room, ballroom, or other event venue within the hotel. |
| venue_type | string | The venue category, such as a meeting room, ballroom, boardroom, or outdoor event space. |
| package_options | array | Meeting, event, or banquet packages available for the venue. |
| capacity_banquet | integer | The number of people the venue can accommodate in a banquet-style layout. |
| capacity_theater | integer | The number of people the venue can accommodate in a theater-style layout. |
| capacity_u_shape | integer | The number of people the venue can accommodate in a U-shaped layout. |
| catering_options | array | Catering services or meal packages available for the venue. |
| available_layouts | array | A list of layout options available for the venue. |
| capacity_boardroom | integer | The number of people the venue can accommodate in a boardroom-style layout. |
| capacity_classroom | integer | The number of people the venue can accommodate in a classroom-style layout. |
| venue_combinations | array | Venues, sections, or configurations that can be combined for use. |
| evidence_references | array | Source excerpts supporting venue facts, together with their locations in the original materials. |
| source_catalog_text | string | The original text of the venue catalog, used as the source for extracting venue facts and supporting evidence. |
| other_layout_capacity | string | Other layout types and their corresponding capacities, with information not specified in the source identified as such. |
| accessibility_features | array | Accessibility provisions and other convenience features associated with the venue. |
| pricing_or_booking_terms | string | Venue prices, fee structures, booking requirements, or applicable conditions; notes when the source does not provide this information. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

