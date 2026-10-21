---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Configuration Change Incident Causal Diagnosis Dataset
---

# Configuration Change Incident Causal Diagnosis Dataset

This dataset covers operational logs for configuration changes, deployments, rollbacks, IT assets, and subsequent incidents, focusing on whether a change caused an incident and what was affected. Each record includes a causal judgment, relationship classification, diagnosis summary, ordered evidence chain, affected assets, alternative causes, and confidence score, supporting analysis of how operational changes lead to failures. It is suitable for configuration change failure diagnosis, incident root cause analysis, and operations postmortems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| confidence | number | Confidence in the causal diagnosis, expressed as a value from zero to one. |
| operation_logs | array | Original change, deployment, rollback, asset, and incident records supplied as input. |
| diagnosis_summary | string | Concise explanation of the causal diagnosis and its operational impact. |
| affected_asset_ids | array | Assets determined from the source logs to have been affected by the change-related incident. |
| alternative_causes | array | Other plausible explanations considered during diagnosis, including why they are less likely or remain unresolved. |
| causal_relationship | string | Classification of the relationship between the change and the incident. |
| causal_evidence_chain | array | Ordered evidence linking the configuration change to deployment or asset effects and then to the observed incident. |
| change_caused_incident | boolean | Whether the analysis concludes that the configuration change caused the subsequent incident. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

