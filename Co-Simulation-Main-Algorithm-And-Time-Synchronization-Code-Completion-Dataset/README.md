---
license: cc-by-nc-sa-4.0
task_categories:
- other
language:
- en
pretty_name: Co-Simulation Main Algorithm and Time Synchronization Code Completion Dataset
---

# Co-Simulation Main Algorithm and Time Synchronization Code Completion Dataset

This dataset focuses on runtime control in co-simulation main algorithms, pairing code contexts that require continuation with target completions and task-type labels. It covers multi-model execution tasks such as communication-point calculation, step advancement, participant-model scheduling, and time synchronization, making it suitable for supervised fine-tuning and code-completion evaluation. The context-to-completion structure helps models learn control logic used in coordinated co-simulation workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| code_context | string | A co-simulation main-algorithm code snippet that the model must understand and continue. |
| target_completion | string | The reference completion corresponding to the code context. |
| completion_task_type | string | The primary task inferred from the code context and target completion, such as communication-point calculation, step advancement, participant-model scheduling, or time synchronization. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

