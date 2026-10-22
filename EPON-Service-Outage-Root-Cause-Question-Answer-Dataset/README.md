---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: EPON Service Outage Root Cause Question-Answer Dataset
---

# EPON Service Outage Root Cause Question-Answer Dataset

This question-answer dataset covers EPON access service outage cases, including alarms, service impact scope, network topology, and related operational clues. Each sample asks the model to combine multiple pieces of evidence to infer a likely fault cause or location and explain the supporting rationale. It supports training and evaluation of abductive reasoning for EPON troubleshooting.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Question asking for the likely outage cause or fault location and its supporting evidence. |
| reasoning | string | Explanation connecting the alarms, impact scope, topology, and operational clues to the diagnosis. |
| confidence | number | Confidence in the diagnosis, expressed as a numeric value from 0 to 1. |
| fault_location | string | Most likely network component or topology location associated with the outage. |
| incident_evidence | object | Structured operational evidence collected for the EPON service outage. |
| probable_root_cause | string | Most plausible technical cause inferred from the supplied evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

