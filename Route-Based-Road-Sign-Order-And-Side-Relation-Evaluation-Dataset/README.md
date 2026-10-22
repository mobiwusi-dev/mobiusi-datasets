---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Route-Based Road Sign Order and Side-Relation Evaluation Dataset
---

# Route-Based Road Sign Order and Side-Relation Evaluation Dataset

This evaluation dataset provides GIS data for route geometry, travel direction, and road signs along each route, with annotations for sign sequence and whether each sign is on the route's left or right. It combines source route and sign records with computed route-relative annotations to assess how well models understand the spatial distribution of road signs along a 2D route. It is suited to spatial-relation evaluation, map-understanding research, and road-scene model validation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| route_source | object | Original route geometry and travel direction used to interpret the route. |
| road_sign_source | array | Original GIS records for road signs located along the route. |
| route_sign_count | integer | Computed number of source road sign records associated with the route. |
| sign_order_annotations | array | Computed route-relative sequence and side labels for the source road signs. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

