---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Zoning Development Intensity and Building Standards JSON Dataset
---

# Zoning Development Intensity and Building Standards JSON Dataset

This dataset pairs zoning standard text or table inputs with structured JSON outputs covering common controls such as building height, setbacks, floor area ratio, lot coverage, and minimum lot requirements. Samples preserve values, units, applicability conditions, and exceptions, while recording the jurisdiction, zoning district, and relevant interpretation notes. It supports planning standard organization, regulatory information extraction, structured data generation training, and output quality evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| standards | array | Normalized development requirements, including numeric values, units, applicability, and exceptions. |
| source_text | string | Original zoning standard text or table content provided as input. |
| jurisdiction | string | Jurisdiction or planning authority associated with the standards, when stated. |
| zoning_district | string | Name or code of the zoning district to which the standards apply. |
| interpretation_notes | array | Notes on ambiguity, normalization choices, or source limitations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

