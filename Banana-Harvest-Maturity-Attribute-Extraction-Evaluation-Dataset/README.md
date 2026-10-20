---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Banana Harvest Maturity Attribute Extraction Evaluation Dataset
---

# Banana Harvest Maturity Attribute Extraction Evaluation Dataset

Focused on the harvest stage of banana production, this dataset contains web text related to harvest maturity, harvest decisions, and postharvest handling, organized around maturity indicators, fruit condition, harvest conditions, decisions, and postharvest measures. It supports evaluation of models that extract banana maturity attributes from specialized text, interpret fruit condition, and connect findings with harvest conditions, as well as research in agricultural information processing and harvest decision support.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| fruit_state | array | The appearance, growth, or maturity condition of the bananas at harvest as described in the source text. |
| source_text | string | The original collected web text about banana harvest maturity or postharvest handling. |
| harvest_decision | string | A summary of whether to harvest or delay harvesting, based on the source text and its stated rationale. |
| harvest_conditions | array | Conditions related to harvesting in the source text and the maturity criteria to which they apply. |
| maturity_indicators | array | Indicators used in the source text to assess banana maturity, including values, units, or evaluation criteria where provided. |
| postharvest_treatments | array | Postharvest handling, storage, transport, or preservation measures for bananas mentioned in the source text. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

