---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Floating Solar PV Electrical Safety and Fault Counterfactual QA Dataset
---

# Floating Solar PV Electrical Safety and Fault Counterfactual QA Dataset

This dataset presents fault and risk scenarios involving cable routing, connectors, insulation, and electrical protection in floating solar PV systems, paired with questions that change a specified condition. Answers examine whether a fault could still occur, how the risk chain and protective response may change, and which conclusions depend on missing information. It supports electrical safety analysis, fault reasoning, and model training or evaluation for reasoning tasks.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct response explaining whether the fault or risk remains possible under the specified change. |
| risk_chain_analysis | string | An explanation of how the changed condition affects electrical hazards, fault propagation, or protective responses. |
| scenario_description | string | The original fault or risk scenario, including relevant cable routing, connectors, insulation, and electrical protection details. |
| evidence_dependencies | string | A statement distinguishing conclusions supported by the provided information from those that depend on unstated assumptions or missing details. |
| counterfactual_question | string | The question specifying a changed condition to assess in relation to the original scenario. |
| fault_persistence_assessment | string | An assessment of whether the original fault could still occur under the counterfactual condition, with appropriate qualifications when information is insufficient. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

