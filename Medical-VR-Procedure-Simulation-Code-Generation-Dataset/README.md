---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Medical VR Procedure Simulation Code Generation Dataset
---

# Medical VR Procedure Simulation Code Generation Dataset

This dataset pairs natural-language requirements for medical training procedures with corresponding VR simulation implementation examples. It covers complete simulation code and modules for state machines, step validation, conditional branching, and completion conditions, highlighting workflow constraints, state transitions, and conditional logic. The examples can support training models to translate medical training requirements into structured simulation logic.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| simulation_code | string | The complete executable VR simulation implementation generated from the procedure requirements, including its overall control flow and state management. |
| state_machine_code | string | TypeScript code defining the procedure states, permitted transitions, and state updates for the VR simulation. |
| branching_flow_code | string | TypeScript code implementing conditional branches in the procedure flow based on user actions, validation results, or simulation state. |
| step_validation_code | string | TypeScript code that checks whether each user action satisfies the requirements for the current procedure step. |
| procedure_requirements | string | The original natural-language description of the medical training procedure, its expected actions, and any relevant constraints. |
| completion_condition_code | string | TypeScript code determining when the procedure or training scenario is complete and handling the resulting completion state. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

