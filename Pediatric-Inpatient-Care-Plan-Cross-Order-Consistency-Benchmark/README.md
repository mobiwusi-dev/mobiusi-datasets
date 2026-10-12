---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Inpatient Care Plan Cross-Order Consistency Benchmark
---

# Pediatric Inpatient Care Plan Cross-Order Consistency Benchmark

This JSON benchmark represents pediatric inpatient care plans with orders for diet, activity, tests, monitoring, and treatment, along with applicable rules for checking relationships among orders. Its annotations identify conflicts, duplicates, and arrangements that cannot be carried out simultaneously, enabling evaluation of a model's ability to reason about constraints across multiple orders. It is suitable for pediatric ward care-plan review, clinical decision support research, and domain-specific medical model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| overall_status | string | The derived overall consistency status of the care plan. |
| care_plan_record | object | The original structured record containing patient context, care orders, and applicable rules. |
| consistency_findings | array | Derived findings that identify conflicting, duplicate, or mutually infeasible orders. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

