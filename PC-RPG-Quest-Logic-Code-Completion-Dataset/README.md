---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: PC RPG Quest Logic Code Completion Dataset
---

# PC RPG Quest Logic Code Completion Dataset

This dataset focuses on PC RPG quest-system implementation, pairing context about quest states, objective conditions, reward rules, and quest-chain dependencies with unfinished code snippets and reference completions. Its examples cover quest logic that depends on game state, supporting training and evaluation of models for understanding and completing quest-system code. It is suited to supervised fine-tuning, game development coding assistants, and quest-logic prototyping.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| completion | string | The reference code continuation that completes the unfinished quest logic and serves as the supervised target. |
| task_context | string | Quest states, objective conditions, reward rules, quest-chain dependencies, and other implementation context provided to the model. |
| incomplete_code | string | The unfinished quest-logic code snippet provided as model input for continuation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

