---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Transmission Diagnostic State Machine Code Verification Dataset
---

# Transmission Diagnostic State Machine Code Verification Dataset

Focused on transmission control unit diagnostics, this dataset provides state machine Python source code, transition constraints, verification results, and annotations for defects and their root causes. It covers fault detection, diagnostic state transitions, and fault recovery, and supports evaluation of constraint compliance, defect localization, and root-cause analysis for automotive software verification and domain-specific model assessment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Python source code for the transmission diagnostic state machine to be verified. |
| defect_count | integer | Total number of state machine defects identified during validation. |
| validation_passed | boolean | Indicates whether the state machine code satisfies the given state transition constraints. |
| diagnostic_defects | array | Defects identified during validation, including their locations, causes, and suggested fixes. |
| root_cause_summary | string | Summary of the main causes of state machine defects and their effects on diagnostics or fault recovery. |
| transition_constraints | string | JSON text specifying permitted diagnostic states, transition conditions, and related constraints. |
| verified_transition_count | integer | Number of state transitions checked during validation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

