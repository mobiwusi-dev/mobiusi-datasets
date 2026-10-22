---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Distributed Trace Event Extraction and Ordering Dataset
---

# Distributed Trace Event Extraction and Ordering Dataset

Designed for application performance management, this dataset provides distributed trace payloads serialized as JSON, covering spans and related events. Annotations identify calls, durations, statuses, and exceptions, then organize them into structured sequences ordered by event time. Use it to train and evaluate models that extract key information from trace data, understand event chronology, and produce structured outputs.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| event_sequence | array | Extracted span and exception events ordered by event time, with a sequence index indicating their chronological position. |
| raw_trace_payload | string | The original distributed trace data serialized as JSON, used as the input source for event extraction. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

