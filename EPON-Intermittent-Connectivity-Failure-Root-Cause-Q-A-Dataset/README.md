---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: EPON Intermittent Connectivity Failure Root Cause Q&A Dataset
---

# EPON Intermittent Connectivity Failure Root Cause Q&A Dataset

Focused on intermittent disconnections and repeated service recovery involving ONUs or user services in EPON access networks, this dataset provides incident reports, alarm and recovery timelines, questions, and root cause analysis answers. It covers the distinction between intermittent and sustained outages, evidence-based ranking of potential causes, and notes on evidence gaps and uncertainty, supporting fault diagnosis from incomplete, changing operational clues. It is suitable for reasoning SFT, access network troubleshooting, and evaluation of operations and maintenance question answering.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| qa_question | string | Question to answer using the incident report and alarm timeline. |
| final_answer | string | Direct response to the question, summarizing the most likely cause and the distinction between intermittent and sustained connectivity issues. |
| alarm_timeline | string | Chronological sequence of alarms, recovery events, and other operational observations relevant to the connectivity issue. |
| incident_report | string | Raw description of the ONU or user service connectivity issue and its observed behavior. |
| uncertainty_notes | string | Evidence gaps, alternative explanations, or limitations that affect the conclusion. |
| likely_root_causes | array | Ranked, evidence-based hypotheses about the cause or causes of connectivity fluctuations. |
| intermittency_classification | object | Assessment of whether the evidence indicates intermittent connectivity, a sustained outage, or an indeterminate pattern. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

