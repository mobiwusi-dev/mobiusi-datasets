---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Hotel Room Type Catalog Matching Benchmark
---

# Hotel Room Type Catalog Matching Benchmark

This benchmark contains pairs of room-type product records drawn from different reservation catalogs, labeled to indicate whether they represent the same room type. Records may include attributes such as bed type, occupancy, room configuration, and view, supporting the identification of equivalent rooms described in different ways and the distinction of similarly named rooms with different configurations. It is designed for catalog matching evaluation, entity resolution, and model performance testing in central reservation systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| match_reason | string | The key room attributes supporting the match or non-match decision. |
| catalog_a_room | object | The original room-type product record from the first reservation catalog. |
| catalog_b_room | object | The original room-type product record from the second reservation catalog. |
| key_differences | array | Configuration differences between the two room records that affect the matching decision; an empty array indicates no notable differences. |
| is_same_room_type | boolean | Evaluation label indicating whether the two catalog records represent the same room type with a consistent configuration. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

