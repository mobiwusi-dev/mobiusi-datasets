---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Out-of-Home Advertising Claim Fact-Verification Dataset
---

# Out-of-Home Advertising Claim Fact-Verification Dataset

This dataset covers product, service, efficacy, pricing, and promotional claims in out-of-home advertising. It provides structured records of ad copy, independently verifiable claim units, evidence requirements, and evidence sources, linking each claim to excerpts, support levels, verification statuses, and rationales before summarizing the overall review. Organized as JSON, it supports fact-verification model training, ad content review, and marketing compliance analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claims | array | The ad text divided into the smallest independently verifiable claim units. |
| ad_text | string | The complete out-of-home ad copy that requires fact verification. |
| evidence_sources | array | Verifiable sources and excerpts used to support, refute, or qualify an ad claim. |
| overall_assessment | object | An overall fact-review conclusion derived from the verification results for individual claims. |
| claim_verifications | array | Records linking ad claims to evidence sources, including support levels, verification statuses, and rationales. |
| evidence_requirements | array | Verification questions, evidence types, and required attributes specified for each ad claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

