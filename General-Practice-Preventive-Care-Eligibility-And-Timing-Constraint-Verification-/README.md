---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: General Practice Preventive Care Eligibility and Timing Constraint Verification Benchmark
---

# General Practice Preventive Care Eligibility and Timing Constraint Verification Benchmark

This JSON benchmark records patient age, risk factors, prior screening or vaccination history, proposed preventive measures, and the applicable criteria, timing intervals, and exclusions. Covering common screening and preventive care decisions in general practice, its records include an eligibility outcome, assessments of individual constraints, and a decision rationale. It supports evaluation of whether models can determine eligibility, timing, and exclusions from the information and rules provided.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| patient_context | object | Patient characteristics and preventive care history used to assess the proposed measure. |
| decision_rationale | string | Concise explanation of the final eligibility assessment, including any decisive timing or exclusion factors. |
| eligibility_status | string | Final benchmark assessment of whether the proposed preventive measure satisfies the supplied constraints. |
| constraint_assessments | array | Assessment of each relevant applicability constraint against the patient's information. |
| applicability_constraints | object | The supplied criteria, timing rules, and exclusions governing whether the proposed measure is appropriate. |
| proposed_preventive_measure | object | The screening, vaccination, or other preventive service being considered for the patient. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

