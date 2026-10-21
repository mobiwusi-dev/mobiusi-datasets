---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: OpenAPI Specification Conformance Benchmark Dataset
---

# OpenAPI Specification Conformance Benchmark Dataset

This benchmark contains OpenAPI specification documents in YAML, their applicable validation rules, and annotations for conformance results, violation locations, and violation counts. It covers requirements such as schema definitions, references, and parameter declarations, enabling evaluation of a model's ability to detect and locate violations with verifiable results. Typical uses include automated conformance checks and quality assurance in API development platforms.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| violations | array | The detected conformance violations and their locations in the OpenAPI document. |
| is_conformant | boolean | Whether the OpenAPI document satisfies all applicable validation requirements. |
| violation_count | integer | The total number of violations found in the OpenAPI document. |
| openapi_document | string | The source OpenAPI specification document in YAML format. |
| validation_profile | object | The source constraints and rules used to evaluate the OpenAPI document. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

