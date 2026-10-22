---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Robotaxi Road Rules and Access Restrictions Relation Extraction Dataset
---

# Robotaxi Road Rules and Access Restrictions Relation Extraction Dataset

Designed for Robotaxi operational maps, this dataset organizes information on road signs, lane access rules, vehicle-class restrictions, and applicable time periods, normalizing regulations from source text into structured rules. It includes road and lane entities, applicable vehicle classes and time periods, directed knowledge graph relations, and extraction confidence scores from 0 to 1. Use it to build and query Robotaxi map knowledge bases and support research on road-rule understanding and access decisions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| relations | array | Directed relations connecting a regulation, road, lane, vehicle class, or time condition. |
| lane_entities | array | Lanes identified as targets or subjects of the extracted rules. |
| road_entities | array | Roads identified as targets or subjects of the extracted rules. |
| regulation_rule | object | Normalized rule extracted from the source material. |
| source_material | string | Original text describing road signs, lane access rules, vehicle restrictions, or applicable conditions. |
| extraction_confidence | number | Confidence score for the extracted rule and its associated relations, ranging from 0 to 1. |
| applicable_time_periods | array | Time intervals or recurring schedules during which the rule applies. |
| applicable_vehicle_classes | array | Vehicle classes to which the rule applies or from which access is restricted. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

