---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Thoracoscopic Lung Resection Step Constraint Verification Benchmark
---

# Thoracoscopic Lung Resection Step Constraint Verification Benchmark

This benchmark represents case context, observed surgical step sequences, and procedural constraints for thoracoscopic and robot-assisted lung resection in structured JSON. It provides validity judgments and specific violation results covering missing required steps, ordering conflicts, and unmet prerequisites. The data supports evaluation of models' thoracic surgical procedural knowledge and constraint-checking capabilities, as well as medical AI benchmarking and surgical workflow research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_valid | boolean | Whether the observed sequence satisfies all supplied ordering, prerequisite, and required-step constraints. |
| case_context | object | The procedure and resection context provided as input for validating the surgical sequence. |
| constraint_set | array | The input constraints specifying required steps, precedence relations, and prerequisite conditions. |
| observed_sequence | array | The ordered list of surgical steps checked against the procedural constraints. |
| validation_summary | string | A concise account of the overall constraint-checking result, including relevant sequence conflicts or omissions. |
| ordering_violations | array | Detected violations of must-precede constraints, including the observed positions of the affected steps. |
| missing_required_steps | array | Required surgical steps that are absent from the observed sequence. |
| precondition_violations | array | Detected instances in which a step was performed before its required prerequisite. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

