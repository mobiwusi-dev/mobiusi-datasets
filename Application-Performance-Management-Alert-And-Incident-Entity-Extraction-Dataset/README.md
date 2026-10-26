---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Application Performance Management Alert and Incident Entity Extraction Dataset
---

# Application Performance Management Alert and Incident Entity Extraction Dataset

This dataset uses alert and failure incident database records from application performance management (APM) systems as input. It includes structured extraction targets for entities such as services, affected components, monitoring items, environments, and error characteristics. The data supports training models to identify and classify domain entities in operational failure records, as well as alert analysis, incident management, and operations knowledge extraction.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_record | string | The original alert or incident database record, serialized as JSON text. |
| entity_mentions | array | Entities identified in the source record, including services, affected components, monitoring items, environments, and error characteristics. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

