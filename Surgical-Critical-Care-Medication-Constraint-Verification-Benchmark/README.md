---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Surgical Critical Care Medication Constraint Verification Benchmark
---

# Surgical Critical Care Medication Constraint Verification Benchmark

This benchmark represents surgical critical care cases in structured JSON, including patient status, medication regimens, and explicit verification constraints covering dosage, allergies, organ function, and drug interactions. Each case provides a compliance judgment, specific violations, a violation count, and a verification summary, supporting evaluation of models that identify medication-regimen issues and produce structured verification results. It is intended for domain-specific model evaluation and medication safety research, not as a substitute for professional clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | Original structured case data containing patient status, medication regimen, and verification constraints. |
| violations | array | Specific constraint violations identified during verification; an empty array indicates that no violations were found. |
| is_compliant | boolean | Indicates whether the medication regimen satisfies all provided constraints. |
| violation_count | integer | Total number of identified violations. |
| verification_summary | string | Concise summary of the verification outcome and its basis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

