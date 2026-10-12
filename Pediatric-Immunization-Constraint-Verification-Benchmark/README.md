---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Immunization Constraint Verification Benchmark
---

# Pediatric Immunization Constraint Verification Benchmark

This benchmark presents structured JSON cases covering a child's age, prior immunization history, immune status, infection or exposure context, proposed vaccination plan, and applicable rules, including age requirements, dose intervals, and contraindications. Each case provides an overall verdict, per-constraint checks, identified violations, and a validation summary to assess models' constraint reasoning and plan verification in pediatric preventive immunization. It is intended for domain evaluation, rule-validation research, and testing clinical decision support systems, not as a substitute for professional medical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | Source case data, including patient context, immunization history, proposed plan, and applicable rules. |
| violations | array | Specific ways the proposed plan fails an applicable rule; empty when no violations are identified. |
| overall_verdict | string | Adjudicated conclusion on whether the proposed plan satisfies the applicable constraints. |
| constraint_checks | array | Per-rule assessment of the proposed plan against each applicable constraint. |
| validation_summary | string | Concise explanation of the adjudication, including material uncertainties when applicable. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

