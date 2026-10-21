---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mineral Processing Sequence and Interlock Code Verification Dataset
---

# Mineral Processing Sequence and Interlock Code Verification Dataset

This dataset focuses on equipment startup and shutdown sequences, operating-state transitions, and control interlock logic in mineral processing. It provides Python source code with validation outcomes, issue categories, and analysis summaries, covering common defects such as invalid state transitions and missing interlock conditions. Root-cause annotations support training and evaluating code verification systems and improving the reliability of industrial control software.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | Summary of the underlying cause of a verification failure or code issue; marked as none when no issue is found. |
| source_code | string | Python source code to be verified, covering mineral processing equipment startup and shutdown sequences, state transitions, or control interlocks. |
| analysis_summary | string | Summary of the code review scope, key verification findings, and supporting evidence. |
| issue_categories | array | Categories of issues identified during code verification; an empty array indicates that no issues were found. |
| validation_status | string | Overall conclusion on whether the source code passes verification of its process and interlock logic. |
| invalid_transitions | array | Invalid equipment state transitions detected in the code, with a brief explanation of each. |
| missing_interlock_conditions | array | Interlock conditions identified during verification that are not covered by the code, with a brief explanation of each. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

