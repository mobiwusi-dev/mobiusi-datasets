---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Affordable Housing Program Rules Fact-Verification Dataset
---

# Affordable Housing Program Rules Fact-Verification Dataset

This dataset pairs claims to be verified with relevant rules from affordable housing program webpages. It covers eligibility conditions, assistance and support rules, housing types, and applicability requirements, with source page text, verdicts, and verification rationales. Designed for expert rule checking in housing and community planning, it supports training and evaluating models on policy fact understanding, evidence comparison, and judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | The fact-checking conclusion reached for the claim based on the program rule evidence. |
| claim_text | string | The original claim that must be checked against housing program rules. |
| claim_domain | string | The housing program rule topic addressed by the claim being verified. |
| housing_type | string | The housing type addressed by the claim or evidence; enter Not mentioned when none is specified. |
| evidence_excerpt | string | An excerpt from the program rules relevant to the claim being verified. |
| source_page_text | string | The original program webpage text containing relevant eligibility, assistance, housing type, or applicability requirements. |
| eligibility_conditions | array | Eligibility conditions identified in the program rules; use an empty array when none are stated. |
| verification_rationale | string | An explanation of how the evidence supports or refutes the claim, or why it is insufficient to reach a conclusion. |
| applicability_requirements | array | Application, residency, income, or other requirements specified by the program rules; use an empty array when none are stated. |
| assistance_or_support_rules | array | Rules for grants, rental assistance, or other housing support offered by the program; use an empty array when none are relevant. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

