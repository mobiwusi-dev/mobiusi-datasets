---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Neuro-Ophthalmology Diagnostic Criteria Constraint Verification Benchmark
---

# Neuro-Ophthalmology Diagnostic Criteria Constraint Verification Benchmark

This structured JSON benchmark contains neuro-ophthalmology case information, examination findings, candidate diagnoses, and corresponding diagnostic criteria, with tasks that check case evidence against each criterion. It focuses on criterion satisfaction, missing evidence, and contradictions, supporting evaluation of models that apply domain rules and produce verification summaries. Typical uses include domain-specific model evaluation, rule-based reasoning research, and structured-output testing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_record | object | Original case information, examination findings, candidate diagnoses, and diagnostic criteria supplied for verification. |
| overall_summary | string | Derived summary of verification across all candidate diagnoses, including important limitations or unresolved evidence. |
| verification_results | array | Derived criterion-by-criterion conclusions for each candidate diagnosis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

