---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Gas Sensor Operating and Fault State Information Extraction Evaluation Set
---

# Gas Sensor Operating and Fault State Information Extraction Evaluation Set

This evaluation set uses text from gas sensor manuals, maintenance guides, and troubleshooting webpages to assess whether models can identify and extract operating or abnormal states such as warm-up, calibration due, over-range, and sensor faults. It focuses on state descriptions, their triggering conditions, and their manifestations, providing a way to measure model understanding and information extraction from specialized gas sensor documents. It supports domain-specific model evaluation, equipment maintenance workflows, and validation of technical document processing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_text | string | Verbatim text from a gas sensor manual, maintenance guide, or troubleshooting webpage used as the extraction input. |
| state_extractions | array | Operating, maintenance, warning, or fault states identified in the source text. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

