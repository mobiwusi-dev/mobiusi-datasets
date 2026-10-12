---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric ADHD Diagnostic Criteria Constraint Verification Benchmark
---

# Pediatric ADHD Diagnostic Criteria Constraint Verification Benchmark

This benchmark uses structured JSON records to capture ADHD symptom evidence in pediatric case materials, including duration, age of onset, reported settings, functional impact, missing information, and contradictions, then checks the evidence against prespecified diagnostic constraints. It supports evaluation of clinical evidence extraction, identification of insufficient or conflicting information, and overall constraint assessment for developmental-behavioral pediatrics applications. Results address only the specified constraints and do not replace professional diagnosis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| missing_items | array | Information required to assess the specified constraints that is absent or insufficiently documented. |
| contradictions | array | Conflicting statements or evidence relevant to the specified diagnostic constraints. |
| duration_months | number | Duration of the relevant symptoms in months, when stated or derivable from the source material. |
| onset_age_years | number | Age in years when the relevant symptoms reportedly began, when stated or derivable. |
| criterion_checks | array | Result for each individual criterion or constraint in the target specification. |
| symptom_evidence | array | Structured, symptom-level evidence extracted from the case material, including the status of each item. |
| reported_settings | array | Distinct settings in which symptoms or related concerns are reported. |
| overall_assessment | string | Overall determination for the prespecified diagnostic constraints, without asserting a diagnosis beyond the reviewed constraints. |
| onset_before_age_12 | boolean | Indicates whether the available evidence supports onset of relevant symptoms before age 12. |
| assessment_rationale | string | Concise synthesis of the overall constraint assessment, including decisive evidence and limitations. |
| source_case_material | string | Original case narrative or source text containing the clinical information to be reviewed. |
| functional_impairment | object | Structured summary of whether symptoms are associated with functional impairment and the evidence supporting that assessment. |
| target_constraint_specification | string | Prespecified diagnostic criteria and constraints against which the case material is evaluated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

