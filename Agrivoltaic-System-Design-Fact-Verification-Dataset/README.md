---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Agrivoltaic System Design Fact Verification Dataset
---

# Agrivoltaic System Design Fact Verification Dataset

This dataset focuses on technical claims about agrivoltaic system structures and design parameters, including module layout, clearance height, row spacing, shading, and light conditions. Its structured JSON records include source evidence, verification labels, and evidence-to-claim relations. They support evaluation of whether models can verify claims against engineering materials, identify how evidence relates to a claim, and provide traceable rationales for benchmark testing and technical document review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | The label indicating whether the cited evidence supports the claim. |
| claim_text | string | The original technical claim about agrivoltaic system structure, layout, clearance, spacing, shading, or light conditions. |
| claimed_unit | string | The unit associated with the claimed value, when applicable; an empty string indicates that no unit is stated. |
| claimed_value | string | The value or qualitative condition asserted by the claim, represented as text to support numeric and nonnumeric claims. |
| claim_category | string | The technical category used to classify the claim. |
| parameter_name | string | The design parameter addressed by the claim, such as module clearance height, row spacing, or shading level. |
| source_evidence | string | The evidence excerpt and any available source citation or location, such as a document title, page, or section. |
| evidence_relation | string | The relationship between the cited evidence and the claim being evaluated. |
| evidence_reference | string | The specific page, section, table, figure, or passage supporting the rationale, when identifiable. |
| verification_rationale | string | A concise explanation connecting specific information in the source evidence to the verdict, rather than relying solely on general domain knowledge. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

