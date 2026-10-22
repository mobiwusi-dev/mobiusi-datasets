---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Dental Treatment Plan Sequencing and Dependency Constraint Benchmark
---

# Dental Treatment Plan Sequencing and Dependency Constraint Benchmark

This benchmark represents dental clinical issues, planned treatment steps, and their dependencies and prerequisites in structured JSON, with labels indicating whether a plan satisfies sequencing constraints. It also records detected ordering conflicts and unmet prerequisites, enabling evaluation of a model's ability to validate constraints across comprehensive dental workflows rather than judge individual treatments in isolation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| sequencing_valid | boolean | Whether the proposed plan satisfies all sequencing constraints and prerequisites. |
| validation_findings | array | Specific sequencing conflicts or unmet prerequisites identified during plan validation. |
| treatment_plan_input | object | The original structured input containing clinical issues, planned treatment steps, and their dependency relationships. |
| sequence_conflict_detected | boolean | Whether the proposed order contradicts an explicit dependency between treatment steps. |
| unmet_prerequisites_detected | boolean | Whether any treatment step lacks a satisfied prerequisite required by the plan. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

