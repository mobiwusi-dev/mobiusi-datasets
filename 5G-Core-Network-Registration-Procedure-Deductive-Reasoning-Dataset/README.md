---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G Core Network Registration Procedure Deductive Reasoning Dataset
---

# 5G Core Network Registration Procedure Deductive Reasoning Dataset

Focused on 5G core network registration procedures, each example provides an initial state, observed messages, and explicit process rules, then asks the model to infer state changes, eligible next steps, or conditions that block progress. Examples include a derived conclusion and its reasoning basis, supporting the development and evaluation of rule-following and deductive reasoning in telecommunications protocol scenarios. Use the dataset for reasoning SFT, procedure logic validation, and 5G core network question-answering applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Records the question to be answered using the states, messages, and process rules. |
| initial_state | string | Records the known core network or registration procedure state at the start of the reasoning task. |
| process_rules | string | Records the explicit rules provided in the prompt for determining state changes, next steps, or blocking conditions. |
| reachable_state | string | Specifies a state reachable under the given rules; may be empty when the question does not involve state inference. |
| reasoning_basis | string | Explains how the conclusion follows from the states, messages, and explicit process rules in the prompt. |
| scenario_context | string | Describes the scenario and relevant context for this registration procedure reasoning example. |
| observed_messages | string | Records the registration procedure messages explicitly provided in the prompt and their order. |
| blocking_condition | string | Specifies a condition that prevents the procedure from continuing or makes the target state unreachable; may be empty if there is no blocker or the question is unrelated. |
| derived_conclusion | string | Provides the direct answer inferred from the prompt, including a reachable state, next step, or blocking determination. |
| applicable_next_step | string | Specifies a next step whose rule prerequisites are met and that can be executed under the current conditions; may be empty if none applies or the question is unrelated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

