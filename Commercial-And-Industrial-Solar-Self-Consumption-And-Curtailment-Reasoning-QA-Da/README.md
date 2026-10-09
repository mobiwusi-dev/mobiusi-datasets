---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial and Industrial Solar Self-Consumption and Curtailment Reasoning QA Dataset
---

# Commercial and Industrial Solar Self-Consumption and Curtailment Reasoning QA Dataset

This dataset presents commercial and industrial solar operating scenarios as text-based questions and answers, covering facility electricity demand, solar generation, grid export limits, and control strategies. It asks models to determine how solar power is self-consumed, exported to the grid, or curtailed, and to explain the conditions behind each conclusion. The data is suited to supervised fine-tuning for logical reasoning and multi-step analysis, as well as model development and evaluation for solar operations and energy management.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | A question based on the original operating scenario that asks the model to determine the relationships among solar self-consumption, grid export, and curtailment. |
| conclusion | string | A concise and clear operating judgment in response to the question. |
| export_relation | string | Explains whether solar power is exported, whether exports are constrained by the grid export limit, and the conditions that apply. |
| reasoning_steps | array | An ordered list of the analysis steps needed to derive the conclusion. |
| source_scenario | string | Source text describing facility electricity demand, solar generation, grid export limits, control strategies, and other relevant operating conditions. |
| self_use_relation | string | Explains how solar generation relates to facility demand and states the conditions under which the self-consumption relationship holds. |
| decisive_conditions | string | Summarizes the demand, solar generation, export limit, control strategy, or other operating conditions on which the conclusion depends. |
| curtailment_relation | string | States whether solar output must be curtailed and explains the operating conditions that trigger curtailment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

