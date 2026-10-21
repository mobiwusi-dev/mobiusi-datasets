---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Nasal and Sinonasal Disease Red-Flag Triage Constraint Evaluation Set
---

# Nasal and Sinonasal Disease Red-Flag Triage Constraint Evaluation Set

This benchmark provides JSON-structured cases for nasal and sinonasal disease triage, covering symptoms, clinical findings, red-flag signals, risk factors, candidate recommendations, and expected disposition constraints. It evaluates whether models recognize signals requiring urgent care or specialist assessment and avoid recommendations that are insufficient for the documented level of risk. The dataset supports rhinology evaluation, triage safety validation, and medical AI development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| symptoms | array | Patient-reported sinonasal symptoms relevant to triage. |
| age_years | number | The patient's age in years, when available in the case record. |
| risk_factors | array | Patient or case characteristics that may affect sinonasal risk assessment and triage. |
| source_record | object | The original JSON case input, including symptoms, examination findings, risk signals, and proposed triage information. |
| red_flag_signals | array | Urgent warning signs or other signals that may require emergency care or specialist assessment. |
| required_actions | array | Actions expected to address urgent risks or arrange appropriate specialist evaluation. |
| clinical_findings | array | Relevant examination findings and other documented clinical observations. |
| undertriage_present | boolean | Whether the candidate recommendation provides a level of care insufficient for the documented risk signals. |
| constraint_rationale | string | A concise explanation of how the case facts and red flags determine the expected triage constraints. |
| expected_safe_disposition | string | The expected level or setting of care appropriate to the case constraints. |
| specialist_assessment_required | boolean | Whether the case constraints indicate that specialist assessment is required. |
| candidate_triage_recommendation | string | The triage advice being evaluated for safety and consistency with the clinical signals. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

