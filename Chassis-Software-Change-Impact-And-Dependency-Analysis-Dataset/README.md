---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Chassis Software Change Impact and Dependency Analysis Dataset
---

# Chassis Software Change Impact and Dependency Analysis Dataset

This dataset focuses on chassis control software source code and localized function or interface changes, providing code reasoning examples and answers that connect change requests and code context to affected callers, downstream logic, and control functions. It shows how to trace impact from a changed symbol through call relationships, data flow, and control flow, and summarizes potential risks and review recommendations. It supports code SFT, chassis electronics maintenance, change reviews, and regression test planning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| change_type | string | A summary of the change, such as an interface signature update, logic modification, parameter change, or return value change. |
| source_code | string | Chassis control software source code used for change impact analysis. It may include relevant functions, interfaces, and call relationships. |
| change_request | string | The localized function or interface change to analyze, which may describe the goal, previous behavior, and proposed modification. |
| changed_symbol | string | The primary function, interface, variable, or other symbol identified from the change input. |
| impact_summary | string | A summary of the primary impact scope, potential behavior changes, and risks that require attention. |
| affected_callers | array | Direct or indirect callers identified through source code dependencies, with explanations of the potential impact. |
| downstream_logic | array | Downstream processing steps, data flows, or conditional branches that may be affected by the change. |
| dependency_reasoning | string | An explanation of how the impact scope is derived from code calls, data transfer, and control flow. |
| review_recommendations | array | Code review, testing, or validation recommendations based on the identified change impact. |
| affected_control_functions | array | Chassis control functions or vehicle behaviors that may be affected by the change. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

