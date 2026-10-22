---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Dental Sedation Safety Constraint Verification Benchmark
---

# Pediatric Dental Sedation Safety Constraint Verification Benchmark

This benchmark uses structured JSON records to capture pediatric dental case histories, preoperative assessments, procedures, proposed sedation plans, and related safety constraints. It labels whether each plan satisfies applicable conditions and identifies unmet requirements. The data supports evaluation of models that check case-specific conditions, detect constraint violations, and explain validation outcomes in pediatric dental sedation scenarios.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | The source JSON record containing the patient's history, preoperative assessment, procedure, proposed sedation plan, and applicable safety constraints. |
| unmet_conditions | array | The applicable safety conditions or constraints that the proposed plan does not satisfy. |
| validation_summary | string | A concise explanation of the validation outcome and the key reasons for any identified constraint violations. |
| constraint_consistent | boolean | Indicates whether the proposed sedation plan is consistent with all applicable constraints in the case. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

