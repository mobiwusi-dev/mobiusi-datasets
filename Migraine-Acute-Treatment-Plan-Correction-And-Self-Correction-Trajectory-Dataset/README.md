---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Migraine Acute Treatment Plan Correction and Self-Correction Trajectory Dataset
---

# Migraine Acute Treatment Plan Correction and Self-Correction Trajectory Dataset

This dataset contains complete agent interaction trajectories for acute migraine treatment planning, including patient context, medication history, treatment risks, initial plans, and the identification of plan errors. Each trajectory shows how an agent responds to cues such as contraindications, drug interactions, or medication overuse by correcting its reasoning and replanning, with the recovery outcome and remaining risks also recorded. The data supports agent recovery training, replanning evaluation, and research on safety behaviors in medical settings; it is intended for model development and evaluation, not as direct clinical guidance.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_plan | object | The acute migraine treatment plan formulated after the agent's self-correction. |
| case_context | object | Patient information, medication history, and treatment-related risk context extracted from the source trajectory. |
| initial_plan | object | The acute migraine treatment plan proposed by the agent before it identifies a problem. |
| recovery_result | object | Records whether replanning was completed and any risks in the revised plan that still require attention. |
| self_correction | object | The agent's explicit process of correcting the initial plan and replanning after identifying an issue. |
| identified_error | object | The error, risk, or inapplicable aspect identified in the initial plan, together with the supporting rationale. |
| source_trajectory | string | The complete original conversation or trajectory between the agent and the user or system about acute migraine treatment planning. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

