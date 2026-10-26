---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cardiac Anesthesia Medication Order Constraint Verification Benchmark
---

# Cardiac Anesthesia Medication Order Constraint Verification Benchmark

This JSON benchmark records cardiac surgery patient and procedure context, applicable medication constraints, and candidate orders for validation. Each case includes labels for whether an order violates a constraint, the violation categories, references to violated constraints, and a validation rationale. It covers constraints such as dose, route, timing, and contraindications, supporting evaluation of structured order checking and violation detection. It is intended for domain evaluation and does not replace clinical judgment or provide instructions for actual medication use.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_violation | boolean | Indicates whether the candidate order violates at least one applicable case-specific constraint. |
| candidate_order | object | The structured medication order evaluated against the patient context and applicable constraints. |
| patient_context | object | Patient and procedure information used to determine which medication constraints apply. |
| validation_rationale | string | A concise explanation linking the patient context and candidate order to the validation result. |
| violation_categories | array | Categories of applicable constraints violated by the candidate order. |
| applicable_constraints | array | Case-specific medication rules against which the candidate order is checked. |
| violated_constraint_references | array | References to the applicable constraints identified as violated by the order. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

