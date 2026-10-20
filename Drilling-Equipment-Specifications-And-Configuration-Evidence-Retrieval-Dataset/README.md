---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Drilling Equipment Specifications and Configuration Evidence Retrieval Dataset
---

# Drilling Equipment Specifications and Configuration Evidence Retrieval Dataset

This dataset organizes parameter lookup and comparison questions around technical specifications, component details, and configuration conditions in drilling and rock excavation equipment manuals, with supporting evidence from tables or text. Each record includes an answer, parameter values and units, applicable configurations, and source location information for verification. It supports retrieval-augmented generation systems that need accurate equipment specification answers with traceable evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query | string | A user question about equipment parameters, component specifications, or configuration conditions; it may request a single value or compare multiple items. |
| answer | string | A technical conclusion derived from the manual evidence, preserving the relevant values, units, and applicable configuration conditions. |
| source_evidence | object | Manual content used as the source evidence for this record, together with its source location information. |
| parameter_evidence | array | A structured list of the parameters covered by the answer, including each parameter value, applicable configuration, and direct supporting evidence from the manual. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

