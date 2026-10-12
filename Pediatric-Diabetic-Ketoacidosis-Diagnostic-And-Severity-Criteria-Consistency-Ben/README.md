---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Diabetic Ketoacidosis Diagnostic and Severity Criteria Consistency Benchmark
---

# Pediatric Diabetic Ketoacidosis Diagnostic and Severity Criteria Consistency Benchmark

This benchmark uses JSON case records containing blood glucose, blood acid-base measures, bicarbonate, ketones, and the diagnostic and severity criteria stated in each case, alongside the recorded diagnostic status and severity. Cases cover findings that support one another, conflict, or are insufficient for a determination, enabling evaluation of whether models verify diagnostic conditions and severity consistently against the given criteria. It is intended for constraint reasoning and specialist model evaluation in pediatric endocrinology, not for clinical diagnosis or treatment advice.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_record | object | The source JSON case record, including measured values, stated criteria, and the recorded diagnosis and severity. |
| criterion_checks | array | Derived checks of individual criteria against the case data. |
| overall_consistency | string | Derived summary of consistency across the recorded diagnostic status and severity. |
| assessment_rationale | string | Concise derived explanation of the overall consistency judgment, limited to the stated criteria and available case data. |
| severity_consistency | string | Derived judgment on whether the recorded severity is supported by the measured data under the severity criteria stated in the case. |
| diagnostic_consistency | string | Derived judgment on whether the recorded DKA status is supported by the measured data under the diagnostic criteria stated in the case. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

