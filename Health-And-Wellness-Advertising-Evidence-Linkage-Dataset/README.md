---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Health and Wellness Advertising Evidence Linkage Dataset
---

# Health and Wellness Advertising Evidence Linkage Dataset

This dataset contains synthetic social media advertising claims about health, nutrition, and wellness, alongside related citations, research or product descriptions, and evidence excerpts. It covers key dimensions such as effect strength, target populations, study conditions, and overgeneralization. Structured annotations connect claims with evidence and assess the degree of support, making the dataset suitable for training and evaluating citation verification, health claim fact-checking, and evidence-grounding capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_material | object | Unprocessed advertising claims, citation text, evidence excerpts, and research or product description context. |
| claim_annotation | object | Structured information derived from advertising claims, including claim type, effects, target populations, and conditions. |
| support_judgment | object | An assessment of the actual support relationship, dimension alignment, and risk of overgeneralization based on comparison of the advertising claim and cited evidence. |
| evidence_annotation | object | Information derived from citations and evidence excerpts, including study type, evidence subject, effects, and study conditions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

