---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Service Application Failure Root Cause Analysis Log Dataset
---

# Multi-Service Application Failure Root Cause Analysis Log Dataset

This dataset contains timestamped log events from multiple services, request-correlation information, and annotations including incident summaries, root cause services, underlying faults, cross-service causal chains, observed symptoms, and diagnostic evidence. Its structured labels distinguish underlying causes from visible symptoms, enabling models to reconstruct how failures propagate through distributed applications, identify root causes, and provide evidence-based explanations. It is suited to application performance management, service reliability analysis, and automated incident diagnosis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| symptoms | array | Observable errors or performance effects reported in the logs, distinct from the underlying cause. |
| confidence | number | Confidence in the root cause assessment, represented as a value from zero to one. |
| log_events | array | Timestamped log entries collected from the services involved in the incident. |
| causal_chain | array | Ordered sequence of events showing how the root cause propagated across services. |
| incident_summary | string | Concise account of the incident inferred from the raw log events. |
| cause_vs_symptoms | object | Explicit distinction between the underlying cause and the observable symptoms of the incident. |
| root_cause_service | string | Service identified as the incident's origin based on the available evidence. |
| root_cause_summary | string | Explanation of the underlying fault that initiated the incident. |
| diagnostic_rationale | string | Evidence-based reasoning connecting the log events to the root cause and causal chain. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

