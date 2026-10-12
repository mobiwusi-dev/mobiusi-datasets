---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Specialty Referral Intake Constraint Validation Benchmark
---

# Specialty Referral Intake Constraint Validation Benchmark

This benchmark represents specialty referral information, intake policies, and validation outcomes in structured JSON. It covers referrals that meet intake criteria as well as cases with missing information, policy conflicts, or triage mismatches. Labels for eligibility, triage alignment, missing requirements, and rule violations support evaluation of models' understanding and constraint reasoning for specialty clinic referrals. It is suitable for healthcare model benchmarking, rule validation, and referral workflow research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_eligible | boolean | Indicates whether the referral meets the specialty eligibility criteria based on the available information. |
| triage_matches | boolean | Indicates whether the referral's urgency and care pathway match the specialty's triage requirements. |
| intake_decision | string | Recommended disposition of the referral based on the validation findings. |
| referral_record | object | Submitted referral details, including clinical context and the requested specialty care. |
| rule_violations | array | Applicable policy rules that the referral fails to satisfy or conflicts with. |
| acceptance_policy | object | Intake requirements and applicable eligibility, exclusion, and triage rules for the requested specialty. |
| validation_status | string | Overall outcome of checking the referral against the applicable intake policy. |
| validation_summary | string | A concise explanation of the validation outcome and recommended disposition. |
| missing_requirements | array | Required information that is absent or insufficient in the referral. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

