---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Adolescent Vaccination Schedule Constraint Verification Benchmark
---

# Adolescent Vaccination Schedule Constraint Verification Benchmark

This benchmark presents structured JSON cases containing adolescent age, prior immunization history, risk information, and proposed vaccination plans, together with explicit, versioned schedule constraints and reference validation outcomes. It covers checks such as vaccination timing, dose intervals, and prior doses, supporting evaluation of constraint reasoning and verification in adolescent preventive care research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| benchmark_case | object | The original adolescent profile, prior immunization history, risk factors, and proposed vaccination plan. |
| benchmark_match | boolean | Whether the computed validation outcome matches the reference expected outcome. |
| computed_validation | object | The validation outcome computed from the case data and the selected schedule constraints. |
| expected_validation | object | The reference validation outcome supplied with the benchmark case. |
| schedule_constraints | object | The explicit, versioned immunization program constraints used to assess the case. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

