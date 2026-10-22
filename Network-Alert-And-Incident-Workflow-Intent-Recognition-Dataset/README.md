---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Network Alert and Incident Workflow Intent Recognition Dataset
---

# Network Alert and Incident Workflow Intent Recognition Dataset

This dataset contains chat messages about network alert and IT incident management, including requests to view alert details, acknowledge alerts, assign incidents, escalate cases, and check resolution status. Records are labeled with the corresponding intent and may include structured details such as alert or incident references, assignees, requested status, priority, and intent confidence. It supports training and evaluating models that interpret operations instructions, identify workflow intents, and extract key action details.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| assignee | string | The person or team assigned to the incident, when specified. |
| priority | string | The priority or severity requested or mentioned in the chat text, when present. |
| chat_text | string | The original user message requesting an alert or incident management action. |
| intent_label | string | The classified intent expressed in the chat text. |
| alert_reference | string | The alert identifier or reference extracted from the chat text, when present. |
| requested_status | string | The incident or alert status requested or mentioned in the chat text, when present. |
| intent_confidence | number | The model confidence score for the assigned intent, expressed from 0 to 1. |
| incident_reference | string | The incident identifier or reference extracted from the chat text, when present. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

