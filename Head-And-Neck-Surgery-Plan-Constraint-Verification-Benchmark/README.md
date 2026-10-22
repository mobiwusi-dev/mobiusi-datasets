---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Head and Neck Surgery Plan Constraint Verification Benchmark
---

# Head and Neck Surgery Plan Constraint Verification Benchmark

This benchmark organizes head and neck surgical cases, proposed plans, and related constraints in JSON, covering anatomical structures, laterality, oncologic requirements, and perioperative safety. Each record labels whether individual constraint categories and the plan as a whole are satisfied, with specific violations and supporting rationale. It supports evaluation of models that validate structured surgical plans, as well as research on verification workflows and structured reasoning; it is not a substitute for clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The original JSON record containing the head and neck surgical case, proposed surgical plan, and stated constraints. |
| violation_details | array | Specific violations identified during validation, including the violated constraint and how the plan conflicts with it. |
| validation_rationale | string | A concise explanation supporting the constraint satisfaction labels and identified violations. |
| all_constraints_satisfied | boolean | Whether every evaluated anatomical, laterality, oncologic, and perioperative safety constraint is satisfied. |
| oncologic_constraints_satisfied | boolean | Whether the proposed surgical plan satisfies the documented oncologic requirements and restrictions. |
| anatomical_constraints_satisfied | boolean | Whether the proposed surgical plan satisfies the documented anatomical constraints. |
| laterality_constraints_satisfied | boolean | Whether the proposed surgical plan uses the correct anatomical side or sides as specified by the case constraints. |
| perioperative_safety_constraints_satisfied | boolean | Whether the proposed surgical plan satisfies the documented perioperative safety constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

