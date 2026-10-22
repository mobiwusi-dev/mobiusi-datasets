---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Obstructive Sleep Apnea Surgical Assessment Constraint Evaluation Set
---

# Pediatric Obstructive Sleep Apnea Surgical Assessment Constraint Evaluation Set

This structured JSON benchmark presents sleep-related symptoms, examination findings, comorbidities, and candidate adenoid or tonsil surgery assessments for children, along with clinical conditions that should be met or checked. It focuses on validating constraints between a proposed assessment and the supplied clinical information, helping identify inconsistencies, insufficient evidence, and information gaps. It supports domain evaluation and validation of medical AI systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| discrepancies | array | Derived conflicts between the proposed assessment and the clinical information, including unsupported or contradictory claims. |
| evidence_gaps | array | Important missing, ambiguous, or insufficiently documented information needed to validate the assessment. |
| clinical_record | object | Recorded patient characteristics, sleep-related symptoms, examination findings, test results, and comorbidities supplied as clinical input. |
| constraint_checks | array | Derived checks of individual clinical conditions, requirements, or claims relevant to the proposed assessment. |
| consistency_status | string | Derived judgment of whether the proposed assessment is supported by, conflicts with, or cannot be adequately evaluated from the recorded information. |
| validation_summary | string | Concise derived explanation of the overall validation outcome and its principal supporting reasons. |
| candidate_assessment | object | The proposed surgical assessment and its stated rationale and conditions, supplied for validation against the clinical record. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

