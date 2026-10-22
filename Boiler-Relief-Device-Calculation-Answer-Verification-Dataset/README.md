---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Boiler Relief Device Calculation Answer Verification Dataset
---

# Boiler Relief Device Calculation Answer Verification Dataset

This dataset uses JSON records to capture boiler operating conditions, equipment constraints, design assumptions, applicable rules, relief-device calculation questions, submitted answers, and reference answers. It also provides normalized inputs, independently calculated results, and answer comparisons for evaluating whether responses meet the stated conditions and rules. The content focuses on capacity, pressure, and unit-related calculations for safety valves and other relief devices, supporting engineering review and automated model evaluation for industrial boilers.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | Original input record containing boiler conditions, design assumptions, applicable rules, the question, the submitted answer, and the reference answer. |
| computed_result | object | Independently calculated relief-device sizing result based on the source conditions and applicable rule. |
| normalized_inputs | object | Derived values converted to consistent units for use in the verification calculation. |
| verification_result | object | Comparison of the submitted answer with the reference answer, evaluated against applicable tolerances. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

