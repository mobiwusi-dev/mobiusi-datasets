---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Battery Management CAN Signal and Source Code Traceability Dataset
---

# Battery Management CAN Signal and Source Code Traceability Dataset

This dataset contains supervised examples tracing CAN signal definitions, encoding and decoding logic, internal variables, and related processing functions in battery management firmware source code. It connects message definitions to implementation details and code locations, providing examples of how signals are handled across firmware. The data supports code fine-tuning, repository understanding, and analysis of CAN signal implementations in battery management control units.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| can_message | object | CAN message definition details identified in or associated with the source code. |
| trace_summary | string | A concise Chinese-language summary of the relationships between message definitions, signal fields, internal variables, and processing functions in the source code. |
| signal_mappings | array | Mappings between CAN signal definitions and firmware variables, encoding or decoding logic, and relevant code locations. |
| source_artifact | object | Firmware source code snippets used for trace analysis, together with their source information. |
| processing_functions | array | A list of firmware function names related to CAN message or signal processing. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

