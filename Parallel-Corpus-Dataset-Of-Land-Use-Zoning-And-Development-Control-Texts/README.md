---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Parallel Corpus Dataset of Land-Use Zoning and Development Control Texts
---

# Parallel Corpus Dataset of Land-Use Zoning and Development Control Texts

This corpus pairs source texts with target-language translations of regulatory clauses from land use planning, including zoning controls, permitted uses, development restrictions, and planning controls. It captures formal regulatory phrasing and cross-language equivalents for planning terminology. Fields for translation instructions, language information, clause categories, and aligned terms support supervised instruction tuning, model training and evaluation, and terminology research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| clause_type | string | Category of the control addressed by the clause, such as zoning, permitted uses, development restrictions, or planning controls. |
| source_text | string | Original land use planning regulation or control clause to be translated. |
| target_text | string | Reference translation in the target language corresponding to the source clause. |
| source_language | string | Name or language code of the language used in the source clause. |
| target_language | string | Name or language code of the language used in the target translation. |
| instruction_text | string | Supervised translation task instruction based on the source and target languages and the planning regulation context. |
| aligned_terminology | string | Corresponding planning terms and expressions in the source and target languages; may include multiple term pairs. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

