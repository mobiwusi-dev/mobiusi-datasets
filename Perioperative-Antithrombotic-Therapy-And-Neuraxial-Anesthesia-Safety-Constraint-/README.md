---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Perioperative Antithrombotic Therapy and Neuraxial Anesthesia Safety Constraint Evaluation Set
---

# Perioperative Antithrombotic Therapy and Neuraxial Anesthesia Safety Constraint Evaluation Set

This benchmark presents structured JSON cases covering anticoagulant or antiplatelet therapy, relevant clinical factors, surgical bleeding risk, and neuraxial procedure plans, together with rules to verify and expected violations. It supports evaluation of a model's ability to identify and verify conflicts involving perioperative medication interruption, procedure timing, and related constraints, for medical AI assessment and safety research. Refer to the accompanying documentation for the sample count and the scope of applicable rules.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The original structured case data supplied for safety evaluation. |
| detected_conflicts | array | Derived list of timing or constraint conflicts identified in the case. |
| overall_safety_status | string | Derived overall assessment of the perioperative antithrombotic and neuraxial plan. |
| rule_evaluation_results | array | Derived assessment of whether each applicable rule is satisfied, violated, or indeterminate based on the source record. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

