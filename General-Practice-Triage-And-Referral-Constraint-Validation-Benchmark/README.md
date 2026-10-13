---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: General Practice Triage and Referral Constraint Validation Benchmark
---

# General Practice Triage and Referral Constraint Validation Benchmark

This benchmark organizes general practice cases in JSON, covering patient symptoms, illness progression, vital signs, red flags, and proposed management or referral levels, together with the applicable triage rules and expected constraint judgments. Focused on urgency assessment and disposition matching in primary care, it supports evaluation of whether models can detect mismatches between patient information and proposed actions, as well as research into constraint reasoning and domain-specific evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| patient_case | object | Patient presentation and proposed disposition provided as the source case data. |
| triage_rules | array | Rules used to assess whether the proposed disposition is appropriate for the case. |
| expected_constraint_judgment | object | Reference assessment based on the patient case, proposed disposition, and applicable triage rules. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

