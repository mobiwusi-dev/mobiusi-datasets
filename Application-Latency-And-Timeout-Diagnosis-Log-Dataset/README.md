---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Application Latency and Timeout Diagnosis Log Dataset
---

# Application Latency and Timeout Diagnosis Log Dataset

This dataset contains application logs recording request latency, processing stages, and timeout events, paired with annotations for total latency, stage timing, primary bottleneck, and root cause. Log evidence is used to trace the causal chain from a performance bottleneck to downstream delays, request impact, or a timeout, helping models move beyond symptom recognition to causal diagnosis. It is suited to log analysis, incident diagnosis, and reasoning training and evaluation in application performance management.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | A causal explanation of why the latency or timeout occurred, grounded in the observed log details rather than merely describing the symptom. |
| application_log | string | The original application log text containing request timing, processing-stage details, and any timeout events. |
| timeout_detected | boolean | Whether the log indicates that the request or one of its processing stages timed out. |
| request_latency_ms | number | The total request latency in milliseconds, extracted from or computed using the application log. |
| bottleneck_location | string | The application component or processing stage identified as the primary performance bottleneck. |
| causal_impact_chain | string | The ordered chain of events linking the bottleneck to downstream delays, request impact, or timeout behavior. |
| diagnosis_confidence | number | The confidence in the causal diagnosis, expressed as a value from 0 to 1. |
| stage_timing_summary | string | A concise summary of the durations and sequence of the request's processing stages, based on the log. |
| supporting_log_evidence | string | Relevant log excerpts or precise log details that support the bottleneck and causal diagnosis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

