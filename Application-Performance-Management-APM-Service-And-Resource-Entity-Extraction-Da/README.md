---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Application Performance Management (APM) Service and Resource Entity Extraction Dataset
---

# Application Performance Management (APM) Service and Resource Entity Extraction Dataset

Focused on Application Performance Management (APM), the dataset covers service catalogs, resource inventories, and associated telemetry database records, with structured examples that identify entities such as application services, hosts, containers, and cloud resources. Canonical entity names are included when the source record provides sufficient information, helping models learn domain-specific entity recognition and classification. It is suitable for structured-output fine-tuning, APM record parsing, and service and resource knowledge development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The original APM service catalog entry, resource inventory item, or associated telemetry database record used for extraction. |
| extracted_entities | array | Application services and infrastructure or cloud resources identified in the source record. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

