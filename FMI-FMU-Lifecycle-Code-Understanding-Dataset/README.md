---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: FMI/FMU Lifecycle Code Understanding Dataset
---

# FMI/FMU Lifecycle Code Understanding Dataset

This dataset focuses on FMI/FMU source code from co-simulation tools, covering lifecycle logic such as instance creation, initialization, stepping, and termination. It pairs code-understanding prompts with reference answers and may include analyses of call sequences, state transitions, and interface responsibilities. The data supports code SFT, code comprehension training, and evaluation of source-code analysis for model integration tools.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A reference explanation answering the understanding task based on the source code, intended for code supervised fine-tuning. |
| source_code | string | FMI/FMU or co-simulation tool source code to analyze. Since the catalog does not provide a code MIME type for the relevant programming language, the content is stored as plain text. |
| task_prompt | string | An analysis question or instruction about the source code, such as explaining creation, initialization, stepping, state changes, or termination logic. |
| call_sequence | string | An explanation of the call order, preconditions, and dependencies among lifecycle-related interfaces or functions. |
| lifecycle_summary | string | A summary of how the code implements the FMI/FMU instance lifecycle from creation through termination, including key behaviors. |
| state_transition_analysis | string | An explanation of instance state changes across lifecycle stages and the supporting evidence in the code. |
| interface_responsibilities | string | An explanation of the responsibilities, inputs, outputs, and roles of relevant FMI/FMU interfaces or functions in the execution flow. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

