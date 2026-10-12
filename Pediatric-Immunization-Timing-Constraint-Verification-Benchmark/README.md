---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Immunization Timing Constraint Verification Benchmark
---

# Pediatric Immunization Timing Constraint Verification Benchmark

This benchmark presents structured JSON cases with a child's age and health conditions, prior immunization records, explicitly provided eligibility ages and dose intervals, contraindications, and a proposed schedule to verify. Annotations report whether the schedule satisfies the stated constraints, identify any violations, and provide a concise validation summary, covering timing and eligibility checks in general pediatric immunization assessment. It supports evaluation and improvement of model reasoning over explicit rules and is not a substitute for clinical judgment or current immunization guidance.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | Original JSON input containing the child's age and conditions, prior doses, explicitly provided rules, and proposed schedule. |
| violations | array | The explicit constraints violated by the proposed schedule; empty when the schedule satisfies all stated constraints. |
| is_compliant | boolean | Whether every proposed dose satisfies the explicitly provided age, dose-interval, and contraindication constraints. This does not mean that unstated series-completion requirements were checked. |
| validation_summary | string | A concise summary of the constraint evaluation based only on the rules provided in the case. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

