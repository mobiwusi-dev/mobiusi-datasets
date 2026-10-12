---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Counterfactual QA Dataset for Grid-Scale Energy Storage Capacity and Duration Planning
---

# Counterfactual QA Dataset for Grid-Scale Energy Storage Capacity and Duration Planning

Designed for grid-scale energy storage planning and reasoning training, this dataset covers storage power, energy capacity, and discharge-duration configurations alongside corresponding grid requirements. Samples compare a baseline configuration with a counterfactual alternative to analyze how power and energy constraints affect feasibility and suitable use cases. The data supports storage option comparison, planning question answering, and training models in counterfactual reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | Answers the original question by clearly comparing the baseline and counterfactual configurations and distinguishing power constraints from energy constraints. |
| scenario_impact | string | Explains how the configuration change affects the grid requirements the storage can meet and the use cases it can serve. |
| source_question | string | Contains the planning scenario and the conditions to compare or the question to answer. |
| grid_requirement | object | Specifies the grid-side power, energy, and duration requirements used to assess whether a storage configuration is feasible. |
| baseline_feasibility | string | Assesses whether the baseline configuration meets the grid requirements under power and energy constraints. |
| baseline_configuration | object | Specifies the storage power, energy capacity, and duration design conditions before the counterfactual change. |
| power_constraint_analysis | string | Compares the power capability of both configurations with the grid requirement and explains whether power is a limiting factor. |
| counterfactual_feasibility | string | Assesses whether the changed configuration meets the grid requirements under power and energy constraints. |
| counterfactual_configuration | object | Specifies the storage power, energy capacity, and duration after the design conditions change. |
| energy_duration_constraint_analysis | string | Compares the energy capacity and duration of both configurations with the grid requirement and explains whether energy or duration is limiting. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

