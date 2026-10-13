---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Primary Care Triage Disposition Safety Constraint Benchmark Dataset
---

# Primary Care Triage Disposition Safety Constraint Benchmark Dataset

This dataset contains structured JSON records of patient presentations, symptoms, vital signs, and candidate dispositions, annotated with assessed urgency, red flags, disposition concordance, and constraint violations. Focused on safety constraints in primary care triage, it helps evaluate whether models can align proposed dispositions with patient risk and explain their assessments. It supports medical AI safety evaluation, triage decision review, and constraint reasoning research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The original JSON record containing the patient's presentation, vital signs, and candidate disposition. |
| urgency_level | string | The urgency level indicated by the patient's presentation and risk information. |
| safety_rationale | string | An explanation of how the patient's presentation and red flags support the disposition assessment. |
| red_flag_findings | array | Symptoms, measurements, or other findings identified as indicators of potential serious risk. |
| constraint_violations | array | Safety constraints or triage requirements that the proposed disposition fails to satisfy. |
| disposition_concordant | boolean | Whether the candidate disposition is consistent with the patient's urgency and risk information. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

