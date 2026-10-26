---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Travel Supplier Data Mapping Debugging Benchmark
---

# Travel Supplier Data Mapping Debugging Benchmark

This benchmark includes travel supplier API responses, source code mapping them to a platform's unified data model, target model structures, and validation cases covering field mappings, enum conversions, and nested data handling. Validation results, issue findings, root cause explanations, and recommended fixes support systematic evaluation of a model's ability to verify mapping logic and diagnose defects. It is designed for cross-supplier data adaptation, integration testing, and mapping quality improvement in travel API aggregation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | Explanation of the underlying cause of mapping or validation failures. |
| recommended_fix | string | Suggested changes to the mapping implementation or related configuration to resolve identified issues. |
| validation_cases | string | Cases and expected outcomes for checking field mappings, enum conversions, and nested structures, serialized as JSON. |
| validation_status | string | Overall result of validating the supplier mapping against the target model and validation cases. |
| validation_summary | string | A concise summary of the checks performed and their outcomes. |
| mapping_source_code | string | Source code that maps a supplier API response to the platform's unified data model. |
| target_model_schema | string | The platform's unified target data model schema, serialized as JSON. |
| supplier_api_payload | string | A sample supplier API response used as input to the mapping implementation, serialized as JSON. |
| field_mapping_findings | string | Findings on missing, incorrect, or misdirected source-to-target field mappings. |
| enum_conversion_findings | string | Findings on invalid or incomplete conversions between supplier enum values and platform values. |
| nested_structure_findings | string | Findings on errors in accessing, transforming, or constructing nested response data. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

