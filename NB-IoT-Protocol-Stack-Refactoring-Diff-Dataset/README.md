---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: NB-IoT Protocol Stack Refactoring Diff Dataset
---

# NB-IoT Protocol Stack Refactoring Diff Dataset

This dataset contains refactoring instructions, original code context, and target code diffs for NB-IoT network-side protocol stacks, covering scenarios such as control-plane protocol handling, state machines, and signaling flows. The diff format makes code changes explicit and provides supervision for models to refactor code while preserving protocol behavior and interface semantics. It is suitable for code SFT, code editing and transformation, and related model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| target_diff | string | The code diff showing the target refactoring changes relative to the original code context. |
| source_code_context | string | The original NB-IoT network-side protocol stack code context relevant to the requested refactoring. |
| refactoring_instruction | string | The instruction describing the requested refactoring while preserving protocol behavior and interface semantics. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

