---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Luxury Hotel Guest Room and Suite Catalog Dataset
---

# Luxury Hotel Guest Room and Suite Catalog Dataset

This dataset contains catalog descriptions of luxury hotel guest rooms and suites, organized into structured attributes such as room type, bed type, maximum occupancy, indoor area, view, accessibility features, and in-room amenities. Each catalog description is paired with extracted attributes, supporting model training and evaluation for distinguishing room types, identifying accommodation details, and producing normalized outputs. Typical uses include hotel catalog management, search and filtering, information extraction, and structured-output SFT.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| view | string | The view available from the room, such as an ocean, city, or garden view. |
| area_sqm | number | The area of the room or suite, converted to square meters. |
| bed_type | string | The bed type and configuration offered in the room, such as a king bed or two twin beds. |
| room_type | string | The guest room or suite category named in the catalog description. |
| max_occupancy | integer | The maximum number of guests permitted in the room, represented as an integer. |
| in_room_amenities | array | A list of in-room facilities and convenience features mentioned in the catalog description; an empty array is returned when no relevant information is available. |
| source_description | string | The original guest room or suite catalog text used as input for attribute extraction. |
| accessibility_features | array | A list of accessibility facilities or adaptations mentioned in the catalog description; an empty array is returned when no relevant information is available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

