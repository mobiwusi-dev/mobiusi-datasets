---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Digital Workspace Authentication and Session Failure Diagnosis Dataset
---

# Digital Workspace Authentication and Session Failure Diagnosis Dataset

This dataset focuses on sign-in and session establishment or interruption issues involving single sign-on, access policies, virtual desktops, and applications, with ordered logs documenting each incident. Records include the failure domain, inferred root cause, key causal steps, an evidence summary, and recommended actions to help models distinguish authentication, authorization, and session-flow problems from log signals. It supports digital workspace operations, incident analysis, and supervised fine-tuning and evaluation of causal reasoning models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | The most likely underlying cause inferred from the log sequence. |
| causal_steps | array | The ordered events and inferences that connect the initial condition to the observed failure. |
| log_sequence | string | The original ordered log entries related to a single sign-on, access policy, virtual desktop, or application session incident. |
| failure_domain | string | The primary layer or component category responsible for the failure. |
| session_outcome | string | The observed result of the sign-in or session flow. |
| evidence_summary | string | A concise explanation of the log signals that distinguish the identified failure domain from other possible causes. |
| recommended_actions | array | Practical diagnostic or remediation actions appropriate to the inferred root cause. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

