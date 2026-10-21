---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Dietary-Constraint-Aware Catering Menu Selection Tool-Use Trajectory Dataset
---

# Dietary-Constraint-Aware Catering Menu Selection Tool-Use Trajectory Dataset

This dataset captures menu-selection workflows for workplace meal delivery, including menu searches, ingredient and allergen checks, identification of diner dietary restrictions, and menu or substitution tool calls. Trajectories include tool requests and responses, feasible menu options, and constraint-satisfaction outcomes, supporting training in evidence-based, stepwise menu selection. It covers the tool-use process from understanding a request through validating a proposed choice, for building dietary-aware catering services.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_trace | array | The ordered sequence of menu, ingredient, allergen, or substitution tool interactions and their outcomes. |
| raw_trajectory | string | The original trajectory serialized as JSON, including menu queries, tool calls, tool responses, and interaction context. |
| dietary_constraints | array | The dietary restrictions or allergy requirements identified for the diner. |
| constraint_satisfied | boolean | Whether the final proposed menu selection satisfies all identified dietary constraints based on the available evidence. |
| conversation_summary | string | A concise summary of the menu-selection request and the actions taken to address it. |
| feasible_menu_options | array | Menu items or substitutions judged suitable after checking the available ingredient, allergen, and dietary information. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

