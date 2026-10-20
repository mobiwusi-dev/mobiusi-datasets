---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: OT Control Command Authorization and State Logic Analysis Dataset
---

# OT Control Command Authorization and State Logic Analysis Dataset

This dataset provides analysis samples based on OT control software source code, covering command receipt, validation, dispatch, and execution, along with authorization checks and device state transitions. Samples address defect locations and evidence, root causes, potential impacts, and remediation recommendations, supporting the identification of missing or bypassed authorization checks and inconsistent state handling. It is suited to OT vulnerability debugging, code review, root-cause analysis, and code SFT.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | Explains the implementation-level causes of missing authorization checks, inconsistent state handling, or other control logic defects. |
| remediation | string | Provides code fixes or safeguards that address the underlying causes of the defect. |
| source_code | string | The OT control software source code snippet under analysis, preserved as provided. |
| command_flow | string | Describes the key steps a control command follows from receipt and validation through dispatch and execution. |
| defect_evidence | string | Quotes or summarizes code logic and triggering conditions that support the defect assessment. |
| defect_location | string | Identifies the affected function, code region, or key statement and explains its relationship to the control flow. |
| impact_assessment | string | Describes potential consequences, such as unauthorized control, incorrect state transitions, or other impacts on OT operations. |
| authorization_analysis | string | Analyzes authorization checks before command execution, including their locations, coverage, and potential gaps or bypasses. |
| state_transition_analysis | string | Describes relevant device states and transition conditions, and assesses potential omissions or inconsistencies in state handling. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

