---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G-Advanced RAN KPI Root Cause Diagnosis Dataset
---

# 5G-Advanced RAN KPI Root Cause Diagnosis Dataset

Focused on 5G-Advanced radio access network operations, this dataset provides textualized cell-level KPI observations, alarms, configuration changes, and operational context in diagnostic question-and-answer examples. Models are asked to infer the most likely issue from potentially incomplete or conflicting network evidence, explain supporting observations and uncertainty, and suggest validation steps. It supports reasoning SFT, network fault analysis, and operations-assisted diagnosis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| network_evidence | string | Textualized cell-level KPI observations, alarms, configuration changes, and operational background provided as input evidence. |
| most_likely_issue | string | The principal inferred RAN problem, stated as a concise root-cause hypothesis. |
| diagnostic_question | string | Question asking for the most likely RAN issue and its justification based on the supplied network evidence. |
| supporting_evidence | string | Explanation of the observations that support the proposed root cause, including relevant KPI, alarm, configuration, or operational details. |
| diagnostic_reasoning | string | Reasoned account of how the evidence was weighed to select the most likely issue over alternative explanations. |
| recommended_validation | string | Suggested checks or measurements that could confirm or refute the inferred root cause. |
| conflicting_or_missing_evidence | string | Discussion of contradictory observations, incomplete evidence, and limitations that affect confidence in the root-cause hypothesis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

