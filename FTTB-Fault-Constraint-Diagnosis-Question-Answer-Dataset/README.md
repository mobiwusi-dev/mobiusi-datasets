---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: FTTB Fault Constraint Diagnosis Question-Answer Dataset
---

# FTTB Fault Constraint Diagnosis Question-Answer Dataset

This dataset contains text-based FTTB fault scenarios with access topology, affected user scope, equipment status, alarms, and troubleshooting results, paired with diagnostic reasoning, excluded causes, supporting evidence, and constrained conclusions. Samples are organized around evidence consistency and network dependencies, making them suitable for training models to analyze faults and rule out unsupported causes when information is limited. Use cases include reasoning SFT, FTTB troubleshooting question answering, network operations support, and constraint-reasoning evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| diagnosis | string | Provides a fault diagnosis consistent with the available evidence and network dependency constraints. |
| reasoning | string | Explains how to analyze the fault scenario using the available evidence and network dependencies. |
| case_input | string | Raw scenario information, including FTTB access topology, affected user scope, equipment status, alarms, and troubleshooting results. |
| excluded_causes | string | Lists fault causes that conflict with the available evidence or network dependencies and explains why they are excluded. |
| supporting_evidence | string | Summarizes the topology, impact scope, equipment status, alarms, or troubleshooting results that support the diagnosis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

