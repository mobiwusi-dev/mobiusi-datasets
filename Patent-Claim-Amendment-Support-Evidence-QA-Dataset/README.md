---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Claim Amendment Support Evidence QA Dataset
---

# Patent Claim Amendment Support Evidence QA Dataset

This dataset organizes question-answer examples around the original disclosure, claims as filed, and amended claims in patent application materials. Answers assess whether amended content is supported and cite relevant disclosure passages or original claims, making the reasoning traceable to source evidence. It is suited to patent examination support, legal text understanding, and domain-specific question-answering model training.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A reasoned response assessing amendment support and explaining the basis for the conclusion. |
| question | string | A question asking whether the amended claim content is supported by the original application and where that support appears. |
| amended_claims | string | The amended claim text being assessed for support in the original application materials. |
| support_status | string | The conclusion on whether the amended content is supported by the provided materials. |
| original_claims | string | The claims as filed, including their numbering and text where available. |
| evidence_references | array | Specific passages from the original disclosure or original claims cited in the assessment. |
| original_application_text | string | The application disclosure as originally filed, serving as the source for assessing support for amendments. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

