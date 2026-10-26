---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: mmWave RAN Fault Root Cause Reasoning Dataset
---

# mmWave RAN Fault Root Cause Reasoning Dataset

This dataset contains fault diagnosis question-and-answer cases for millimeter-wave radio access networks, with cross-layer evidence such as alarm records, performance metrics, configuration states, and field observations. It also provides candidate-cause comparisons, root cause assessments, evidence chains, and explanatory answers. The data supports training and evaluating models that reason from network evidence, rank possible causes, and produce grounded diagnostic conclusions for network operations assistance.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| confidence | number | The estimated confidence in the selected root cause, represented as a value from 0 to 1. |
| root_cause | string | The selected most likely root cause inferred from the available cross-layer evidence. |
| alarm_evidence | object | Raw alarm records, including alarm codes, severity, timestamps, affected cells, beams, or network elements. |
| evidence_chain | array | Ordered evidence statements connecting the raw observations to the selected root cause. |
| candidate_causes | array | The original list of possible fault causes to consider when answering the diagnostic question. |
| reasoning_answer | string | An explanatory answer describing the diagnostic logic, evidence interpretation, and why alternative causes are less likely. |
| field_observation | string | Original field notes describing symptoms, environmental conditions, recent changes, or troubleshooting observations. |
| configuration_state | object | Raw configuration values and status information for relevant cells, beams, carriers, handovers, and network functions. |
| diagnostic_question | string | The original question asking for a fault diagnosis or comparison of possible causes. |
| performance_metrics | object | Raw performance measurements relevant to the incident, such as throughput, BLER, latency, PRB utilization, or signal quality. |
| ranked_cause_assessments | array | A comparison of candidate causes, ranked by how well each is supported by the available evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

