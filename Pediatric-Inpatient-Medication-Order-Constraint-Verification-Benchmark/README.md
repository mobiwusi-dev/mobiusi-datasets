---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Inpatient Medication Order Constraint Verification Benchmark
---

# Pediatric Inpatient Medication Order Constraint Verification Benchmark

This JSON benchmark represents pediatric inpatient cases with patient age, weight, relevant medical history, medication orders, and explicitly stated constraints. Annotations indicate whether an order meets requirements such as dose ranges, single-dose or daily maximums, and eligibility conditions, while identifying violations or information gaps that prevent assessment. It supports evaluation of rule checking and constraint reasoning in pediatric medication scenarios, as well as research on prescription validation and clinical decision support; it is not a substitute for professional clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | The original patient context, medication order, and applicable constraints provided for evaluation. |
| violations | array | Specific ways in which the medication order violates an applicable, explicitly provided constraint. |
| overall_status | string | The derived overall conclusion about whether the medication order satisfies the provided constraints. |
| information_gaps | array | Missing or ambiguous information that prevents reliable evaluation of one or more constraints. |
| constraint_checks | array | A rule-by-rule evaluation of the medication order against the explicitly provided constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

