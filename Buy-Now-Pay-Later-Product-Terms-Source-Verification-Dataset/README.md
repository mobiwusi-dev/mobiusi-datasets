---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Buy Now, Pay Later Product Terms Source Verification Dataset
---

# Buy Now, Pay Later Product Terms Source Verification Dataset

This dataset covers buy now, pay later claims about repayment schedules, fees, late-payment handling, and user eligibility, paired with related provider webpage terms and agreement text. Each record includes a claim category, a source-support verdict, an assessment of source authority, evidence quotations, and a verification rationale, supporting the training and evaluation of models that verify claims against web evidence and assess source reliability. It is suited to fintech, consumer credit, and information reliability research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The buy now, pay later product claim to be checked against the cited source. |
| claim_category | string | The buy now, pay later product topic addressed by the claim. |
| evidence_quotes | array | Key excerpts from the webpage terms that support or contradict the claim being verified. |
| source_material | object | Provider webpage information and terms or agreement text used to verify the claim. |
| support_verdict | string | Indicates whether the cited webpage terms support, contradict, or do not determine the claim. |
| authority_assessment | string | Explains the source's relationship to the relevant provider and the basis for its authority assessment. |
| verification_rationale | string | Explains the support verdict by connecting the claim with the webpage evidence. |
| is_authoritative_source | boolean | Indicates whether the cited webpage is an authoritative information source for the relevant provider. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

