---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Neurosurgical Procedure Sequence Constraint Evaluation Dataset
---

# Neurosurgical Procedure Sequence Constraint Evaluation Dataset

This JSON-structured benchmark represents neurosurgical procedure steps and their prerequisites, dependencies, incompatibilities, and ordering constraints, alongside candidate sequences and reference violation labels. It supports evaluation of a model’s ability to detect ordering errors, missing dependencies, and constraint conflicts, and is designed for structured constraint verification and domain benchmarking.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| candidate_sequence | array | The proposed ordered sequence of procedure step identifiers to be checked against the defined constraints. |
| procedure_constraints | object | The defined procedure steps and their prerequisite, dependency, incompatibility, and ordering constraints. |
| constraint_check_summary | object | A computed summary of whether the candidate sequence satisfies the procedure constraints. |
| reference_violation_labels | array | The benchmark-provided standard labels identifying constraint violations in the candidate sequence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

