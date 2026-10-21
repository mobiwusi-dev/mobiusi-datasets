---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Agreement Claims and Evidence Sufficiency Dataset
---

# Lease Agreement Claims and Evidence Sufficiency Dataset

This dataset pairs factual claims about lease agreements with corresponding documentary excerpts and labels whether the evidence is sufficient to support each claim. Annotations cover direct support, completeness, missing evidentiary basis, and assessment rationale. It supports training and evaluation of legal-document verifiers that check the evidentiary basis for lease-related facts.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The specific factual claim made about the lease agreement. |
| missing_basis | string | The necessary factual or documentary basis absent from the excerpt, or an empty string if none is missing. |
| direct_support | boolean | Whether the excerpt directly supports the claim rather than requiring an unsupported inference. |
| complete_support | boolean | Whether the excerpt contains all information necessary to support the full claim. |
| evidence_excerpt | string | The verbatim or faithfully transcribed lease document passage offered in support of the claim. |
| assessment_rationale | string | A concise explanation connecting the excerpt's contents to the sufficiency judgment. |
| evidence_sufficiency | string | Whether the excerpt provides sufficient support for the claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

