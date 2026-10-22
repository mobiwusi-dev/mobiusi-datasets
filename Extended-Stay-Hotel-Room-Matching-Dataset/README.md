---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Extended-Stay Hotel Room Matching Dataset
---

# Extended-Stay Hotel Room Matching Dataset

This dataset pairs extended-stay hotel room or suite catalog listings with guest queries describing accommodation needs, then labels how well each listing matches the query. Requirements may include party size, kitchen or laundry facilities, and space needs. Match status, a score from 0 to 1, and a concise explanation support lodging search, recommendation, and query-document matching evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| guest_query | object | The source search request describing a guest's extended-stay requirements. |
| match_score | number | A derived score from 0 to 1 representing the degree of match between the room type and the guest query. |
| match_status | string | The derived categorical assessment of how well the room type satisfies the guest query. |
| match_explanation | string | A concise derived explanation identifying which guest requirements are satisfied or unmet. |
| room_type_listing | object | The source catalog entry describing an extended-stay room type or suite. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

