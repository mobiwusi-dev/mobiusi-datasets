---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mine Block Model Construction and Processing Code Generation Dataset
---

# Mine Block Model Construction and Processing Code Generation Dataset

This dataset provides examples of constructing and processing block models in mine resource modeling software from natural-language specifications. The examples cover model bounds, grid parameters, subblock settings, attribute fields, and model operations, linking text requirements with derived parameters, operation steps, and generated scripts or macros. It supports training and evaluating models for mining software assistance, modeling workflow automation, and code generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| model_bounds | object | Derived spatial limits of the block model. |
| generated_code | string | Script or macro generated to implement the requested block model construction or processing task. |
| grid_parameters | object | Derived parent cell dimensions, counts, and orientation for the model grid. |
| attribute_fields | array | Attribute fields to create or populate in the block model. |
| model_operations | array | Ordered operations for constructing or processing the block model. |
| subblock_settings | object | Derived cell subdivision rules and subblock dimensions. |
| assumptions_and_notes | array | Assumptions, unresolved details, or implementation notes relevant to the model or generated code. |
| requested_specification | string | Original natural-language requirements for the block model construction or processing task. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

