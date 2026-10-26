---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: International News Event Developments and Timeline Extraction Dataset
---

# International News Event Developments and Timeline Extraction Dataset

This dataset brings together multiple reports or follow-up updates about the same international news event and annotates them in JSON with an event summary, stages and developments, temporal relationships, and supporting source evidence. It preserves material differences across reports so models can distinguish source-specific claims instead of merging inconsistent information into a single account. It is designed for structured-output fine-tuning, news event tracking, fact-checking, and information extraction evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| event_summary | string | A concise summary of the shared event, limited to information supported by the source materials. |
| timeline_events | array | Chronological or explicitly ordered event stages and developments, each with timing, relationships, a description of changes, and supporting evidence. |
| source_materials | string | Original news reports or updates provided as input, including available publication metadata and article text. |
| cross_report_conflicts | array | Material differences among reports, recorded explicitly rather than resolved by merging incompatible claims. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

