---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ITSM Incident Root Cause Analysis Log Dataset
---

# ITSM Incident Root Cause Analysis Log Dataset

Covers raw incident logs from IT service disruptions, chronological event details, status changes, response actions, and recovery records, with annotated symptoms, root-cause judgments, causal chains, and diagnostic reasoning. Log evidence connects triggering conditions, incident progression, and service impact, supporting models that distinguish symptoms from root causes and perform temporal causal analysis and failure diagnosis. The dataset is suited to ITSM reasoning fine-tuning, operations troubleshooting, and post-incident reviews.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | The most likely underlying cause of the incident, based on evidence in the logs. |
| causal_chain | array | Ordered sequence connecting precipitating conditions, causal events, and resulting symptoms or impact. |
| event_timeline | array | Chronological reconstruction of key events, status changes, response actions, and their outcomes. |
| recovery_summary | string | Summary of remediation, verification, and service restoration recorded in the incident logs. |
| observed_symptoms | array | User-facing or system-observed symptoms, distinguished from their underlying causes. |
| raw_incident_logs | string | Original incident log text containing timestamped events, status changes, response actions, and recovery records. |
| diagnostic_reasoning | string | Explanation of how log evidence supports the root-cause judgment and distinguishes causes from symptoms. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

