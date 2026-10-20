---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: NB-IoT Code Change Impact Dependency Reasoning Dataset
---

# NB-IoT Code Change Impact Dependency Reasoning Dataset

This dataset contains NB-IoT network software source code, local code change examples, and supervised question-answer pairs about the resulting impact scope, including affected functions, software modules, and call paths. Samples use code context and dependency relationships to help models reason about how changes propagate across components. It is suitable for NB-IoT protocol stack maintenance, code review, and supervised fine-tuning or evaluation of code reasoning models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise response to the impact question summarizing the scope of the change. |
| source_code | string | NB-IoT software source code provided as context for analyzing the impact of a change. |
| change_example | string | A local code change, patch, or modified code fragment to analyze. |
| impact_question | string | A question asking which functions, modules, or call paths may be affected by the change. |
| affected_modules | array | NB-IoT software modules identified as potentially affected by the code change. |
| impact_reasoning | string | Dependency-based explanation of how the change may propagate to the identified functions, modules, or call paths. |
| affected_functions | array | Functions identified as potentially affected by the code change. |
| impacted_call_paths | array | Call paths linking the changed code to affected functions or modules. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

