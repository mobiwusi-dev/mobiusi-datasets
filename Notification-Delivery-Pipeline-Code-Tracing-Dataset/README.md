---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Notification Delivery Pipeline Code Tracing Dataset
---

# Notification Delivery Pipeline Code Tracing Dataset

Focused on source code from enterprise notification and broadcast communication platforms, this dataset covers delivery stages such as request handling, queue scheduling, channel dispatch, and status callbacks. Samples use tracing questions, call paths, flow summaries, and key data flows to explain component responsibilities, execution order, and how data moves through the pipeline. It supports code understanding and code SFT training, as well as code retrieval, workflow analysis, and developer learning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | Answer to the tracing question, using the call path and data flows to explain the responsibilities and connections between delivery stages. |
| call_path | array | Functions, methods, or handlers involved in notification delivery, listed in execution order. |
| data_flow | array | Sources, transformations, and destinations of notification data as it moves through the workflow. |
| source_code | string | Source code snippet used to trace notification request handling, queue scheduling, channel dispatch, or status callbacks. |
| flow_summary | string | Summary of the overall notification delivery process, from incoming request to dispatch completion or status callback. |
| user_question | string | Question about understanding the notification delivery workflow represented by the source code. |
| pipeline_stages | array | Responsibilities and connections between stages such as request handling, queue scheduling, channel dispatch, and status callbacks. |
| status_callback | string | Explanation of how dispatch results are written back, trigger callbacks, or update notification status; explicitly states when the workflow has no callback. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

