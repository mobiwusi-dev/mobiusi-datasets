---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: XGS-PON Alarm Correlation and Root-Cause Inference Q&A Dataset
---

# XGS-PON Alarm Correlation and Root-Cause Inference Q&A Dataset

This question-and-answer dataset covers alarms and status changes across OLTs, PON ports, and ONUs in XGS-PON access networks, with events presented in chronological order. Its examples trace alarm relationships, identify a likely initiating fault and downstream effects, and distinguish root causes from accompanying symptoms. It is designed for reasoning SFT, fault-causality analysis, and XGS-PON operations workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | string | Chronological account of alarms and status changes across the OLT, PON port, and ONU, together with the question to be answered. |
| root_cause | string | Identifies the most likely initiating fault and explains the assessment using the event sequence and device states in the case. |
| final_answer | string | Complete user-facing conclusion combining the alarm relationships, likely root cause, downstream effects, and distinction between cause and symptoms. |
| downstream_effects | string | Describes subsequent alarms and status changes that may result from the initiating fault, including effects on ports or ONUs. |
| reasoning_rationale | string | Summarizes the key event sequence, status changes, and evidence used to correlate alarms, infer a root cause, and rule out alternative explanations. |
| related_alarm_chain | string | Chronological account of related alarms and status changes, including their causal or correlational relationships. |
| symptom_classification | string | Distinguishes the most likely root cause from resulting or concurrent symptoms and explains the basis for the distinction. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

