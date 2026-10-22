---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Change-Induced Incident Causal Diagnosis Log Dataset
---

# Change-Induced Incident Causal Diagnosis Log Dataset

This dataset brings together ITSM change records and related deployment, configuration, service, and incident logs, with supervised labels for incident outcomes, the change's causal role, potential failure mechanisms, and supporting evidence. Causal chains, temporal assessments, supporting or contradicting observations, alternative explanations, and diagnostic rationales help models distinguish causal evidence from mere temporal proximity. It supports IT operations troubleshooting, change-impact reviews, and the training and evaluation of causal-reasoning models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Specific observations from the raw records that support, contradict, or contextualize the causal diagnosis. |
| diagnosis | object | The supervised assessment of the incident outcome, the change's causal role, confidence, and the proposed failure mechanism. |
| causal_chain | array | Ordered events that explain the proposed path from the change to the service outcome. Include only evidence-supported links and identify uncertain links in their descriptions. |
| change_record_raw | string | The original ITSM change record serialized as JSON, including its identifier, scope, planned timing, implementation details, and status when available. |
| temporal_assessment | object | An assessment of event ordering and timing. Timing can establish consistency with a hypothesis but does not by itself establish causality. |
| diagnostic_rationale | string | A concise reasoning summary connecting the evidence, causal mechanism, temporal assessment, and alternatives to the final attribution. Do not infer causality from temporal proximity alone. |
| operational_logs_raw | string | Original deployment, configuration, service, and incident events serialized as JSON Lines, preserving timestamps and observed states when available. |
| recommended_validation | array | Checks that could confirm or refute the diagnosis, such as comparing pre- and post-change state, reviewing correlated telemetry, or reproducing the behavior. |
| alternative_explanations | array | Plausible non-change causes or competing explanations considered, with a concise account of whether the available evidence supports or weakens each one. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

