---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Retail Foreign Exchange Risk Disclosure Translation Dataset
---

# Retail Foreign Exchange Risk Disclosure Translation Dataset

This dataset contains retail foreign exchange risk warnings, product disclosures, and customer notices paired with their translations. Each record includes a faithful translation instruction, language metadata, and a disclosure category, with an emphasis on preserving risk qualifiers, warning tone, and financial terminology. It supports translation instruction tuning and evaluation without treating translation as legal interpretation or cross-jurisdictional rule adaptation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_text | string | The original retail foreign exchange risk disclosure, product disclosure, or customer notice text to be translated. |
| disclosure_type | string | The category of the record, such as a risk warning, product disclosure, or customer notice. |
| source_language | string | The language of the original disclosure text. |
| target_language | string | The language used in the reference translation. |
| reference_translation | string | The translation paired with the source text, intended to preserve its meaning, risk qualifiers, warning tone, and financial terminology. |
| translation_instruction | string | The instruction for producing a faithful translation without adding legal interpretation or adapting rules across jurisdictions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

