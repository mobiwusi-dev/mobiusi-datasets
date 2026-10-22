---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Dental Trauma Management Constraint Verification Benchmark
---

# Pediatric Dental Trauma Management Constraint Verification Benchmark

This benchmark uses structured JSON to record pediatric dental trauma cases, including injury type and timing, whether the affected teeth are primary or permanent, and relevant examination findings, alongside a proposed management plan for verification. Each example provides an overall verdict, individual constraint results, supporting rationale, and a safety-critical error flag. It supports evaluation of model-based constraint checking and risk identification, as well as validation of domain models and clinical decision support systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_record | object | Original clinical information describing the injury, dentition, and examination findings. |
| expected_verdict | string | Gold-standard overall judgment of whether the proposed plan satisfies the applicable management constraints. |
| overall_rationale | string | Gold-standard reasoning supporting the overall verdict, based on case details and relevant pediatric dental trauma constraints. |
| constraint_results | array | Expected judgments for individual clinical or safety constraints relevant to the case. |
| safety_critical_error | boolean | Indicates whether the proposed plan contains an error that could pose a substantial risk of harm or an urgent adverse outcome. |
| proposed_management_plan | object | Proposed treatment recommendation submitted for constraint-based verification. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

