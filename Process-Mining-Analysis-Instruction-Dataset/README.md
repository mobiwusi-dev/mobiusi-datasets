---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Process Mining Analysis Instruction Dataset
---

# Process Mining Analysis Instruction Dataset

This dataset contains natural-language requests for analyzing process performance, paired with labels for analytical intent and structured parameters covering process scope, metrics, filters, time ranges, and grouping dimensions. It focuses on understanding and formalizing analysis requests rather than providing analysis results, making it useful for training models to turn business instructions into clear analysis specifications. Typical uses include instruction tuning, process analytics assistant development, and evaluation of request-parsing capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| analysis_intent | string | The primary analytical goal inferred from the user's instruction. |
| instruction_text | string | The user's original natural-language request for process analysis. |
| analysis_parameters | object | Structured parameters specifying the process scope, metrics, filters, time range, and grouping dimensions for the requested analysis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

