---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G-Advanced RAN Scheduler Code Debugging Dataset
---

# 5G-Advanced RAN Scheduler Code Debugging Dataset

Focused on 5G-Advanced radio access network (RAN) schedulers and related control logic, this dataset includes source code snippets for inspection, debugging tasks, issue validation labels, and root-cause examples. It covers code verification issues such as resource allocation, boundary conditions, and scheduling priorities, with expected behavior and repair suggestions. Use it to train and evaluate coding agents that detect scheduling logic defects, identify their causes, and propose code-level fixes.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| issue_type | string | Category of the code issue, such as resource allocation, boundary condition, or scheduling priority. |
| root_cause | string | Explains the implementation flaw and its effect on scheduling behavior. |
| source_code | string | Source code snippet from a scheduler or related control logic that needs inspection. |
| bug_location | string | Verified location of the issue, such as a function, code line, or logic branch. |
| task_description | string | Specifies the scheduling logic to verify, expected behavior, or issue to investigate. |
| expected_behavior | string | Describes the scheduling or control behavior expected from a correct implementation. |
| repair_suggestion | string | Provides code-level guidance or an implementation approach for fixing the issue. |
| validation_target | boolean | Indicates whether validation found an issue in the scheduling or control logic. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

