---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Health and Wellness Advertising Claim Verification Dataset
---

# Health and Wellness Advertising Claim Verification Dataset

This dataset contains synthetic social media advertisements about health, nutrition, fitness, and beauty, covering claims about benefits, risk reduction, ingredient effects, and scientific outcomes. Each advertisement is paired with extracted claims, an overall verification label, evidence sufficiency assessments, knowledge evidence, and risk warnings to support analysis of factual credibility and scientific support. It is suited to health information fact-checking, advertising review, and knowledge-grounding research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claims | array | Specific claims extracted and separated from the advertisement, including benefit, risk reduction, ingredient effect, or scientific outcome claims. |
| claim_count | integer | Number of distinct claims identified in the advertisement text. |
| risk_warnings | array | Potentially misleading risks, scope limitations, or health safety cautions identified during claim verification. |
| evidence_score | number | Numerical score for the overall sufficiency of evidence supporting the advertisement's claims, on a scale from 0 to 1. |
| advertisement_text | string | Synthetic social media advertisement text about health, nutrition, fitness, or beauty to be analyzed. |
| knowledge_evidence | array | Guidelines, systematic reviews, clinical studies, or other scientific evidence used to support or challenge the advertisement's claims. |
| advertisement_domain | string | Main health and wellness topic area identified from the advertisement. |
| contains_medical_claim | boolean | Indicates whether the advertisement includes claims related to disease prevention, treatment, diagnosis, or medical effects. |
| overall_verification_label | string | Assessment of the advertisement's overall credibility based on all of its claims. |
| overall_evidence_sufficiency | string | Assessment of the overall sufficiency of scientific evidence needed to support the advertisement's main health claims. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

