---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Implant-Supported Prosthesis Component Compatibility Verification Benchmark
---

# Implant-Supported Prosthesis Component Compatibility Verification Benchmark

This benchmark uses structured JSON to represent implant connection information, a restorative component catalog, case requirements, and proposed designs for evaluation. It includes compatible and incompatible combinations, with triggered constraints and explanations, to assess component matching and consistency with case-specific conditions in implant-supported restorative design. It supports domain-specific model evaluation, design review workflow validation, and prosthodontic research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| proposed_design | object | Specification of the component combination and retention approach being evaluated. |
| case_requirements | object | Clinical and restorative constraints that the proposed design must satisfy. |
| component_catalog | array | Source catalog of restorative components available for the proposed design. |
| assessment_summary | string | Concise summary of the compatibility assessment and its principal reasons. |
| implant_connection | object | Source information describing the implant system and its restorative connection interface. |
| compatibility_status | string | Overall compatibility classification for the proposed design and case. |
| triggered_constraints | array | List of constraints violated or conditionally triggered by the proposed design, with explanations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

