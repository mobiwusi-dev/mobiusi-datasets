---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Network Configuration Change Record Entity Extraction Dataset
---

# Network Configuration Change Record Entity Extraction Dataset

This dataset centers on configuration change records from network and systems management software, including change summaries, descriptions, and related record fields. It provides structured entities and types for devices, interfaces, configuration objects, protocols, and software, supporting model training to identify key objects in operational text. It is suitable for network operations record processing, configuration change analysis, and development of related intelligent tools.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| entity_count | integer | The total number of entities in extracted_entities. |
| extracted_entities | array | Entities identified in the source record, including devices, interfaces, configuration objects, protocols, and software. |
| source_record_json | string | The original configuration change record serialized as JSON, including its summary, description, and record fields. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

