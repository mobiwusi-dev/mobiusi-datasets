---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Rheumatology Medication Order Constraint Verification Benchmark
---

# Pediatric Rheumatology Medication Order Constraint Verification Benchmark

This benchmark represents patient age, weight, medication regimens, doses, administration frequency, and relevant examination information in structured JSON, with verification conditions such as dose ranges, maximum doses, and contraindications for each case. It evaluates whether models can verify pediatric rheumatology medication orders against specified constraints, identify inconsistencies, and locate violations. It is intended for domain-specific model evaluation and medical AI safety research, not for treatment recommendations or clinical decision-making.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| violations | array | Structured list of the inconsistencies found, including their location and the applicable expected condition. |
| input_record | object | Original structured patient, medication order, and verification constraint data for one benchmark case. |
| violation_count | integer | Number of distinct constraint violations identified in the order. |
| validation_status | string | Overall benchmark result indicating whether the supplied medication order satisfies the specified constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

