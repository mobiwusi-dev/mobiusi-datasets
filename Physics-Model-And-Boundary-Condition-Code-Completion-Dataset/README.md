---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Physics Model and Boundary Condition Code Completion Dataset
---

# Physics Model and Boundary Condition Code Completion Dataset

Designed for physics and engineering simulation workflows, this dataset provides code contexts and completion targets for physics-field selection, material properties, initial conditions, and boundary conditions. Samples are organized with task instructions, code snippets, and complete completion text, alongside labels for physics-setting categories and identifiable simulation software or coding environments. It supports code SFT, simulation-configuration assistants, and evaluation of engineering code generation and completion.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| code_context | string | Code snippet preceding the completion target, provided to help the model understand the current engineering simulation setup. |
| task_instruction | string | Describes the physics model or boundary condition code completion task. |
| completion_target | string | Complete code text used as the supervised completion target, including the model or condition configuration to generate. |
| simulation_software | string | Engineering simulation software or coding environment identified from the code; enter unknown when it cannot be determined. |
| physics_setting_categories | array | Physics configuration categories extracted from the code context or completion target, which may include physics fields, material properties, initial conditions, and boundary conditions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

