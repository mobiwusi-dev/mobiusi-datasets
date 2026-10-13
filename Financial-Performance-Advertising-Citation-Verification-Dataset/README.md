---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Financial Performance Advertising Citation Verification Dataset
---

# Financial Performance Advertising Citation Verification Dataset

This dataset contains synthetic financial advertising text covering returns, interest rates, savings, risk performance, and guarantee-related claims, paired with evidence excerpts that explain calculation periods, applicable conditions, limitations, or risk disclosures. Records organize claims, evidence elements, claim-to-evidence links, and an overall support verdict, enabling training and evaluation of models that verify financial advertising claims and their qualifications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claims | array | Verifiable financial claims identified in the advertising text, including their figures, periods, and qualifications. |
| ad_text | string | Original advertising text containing claims about financial returns, interest rates, savings, risk performance, or guarantees. |
| evidence_text | string | Original calculation notes, conditions, limitations, risk disclosures, or other evidence used to support or qualify advertising claims. |
| evidence_elements | array | Figures, periods, conditions, limitations, and risk or guarantee-related statements extracted from the evidence excerpt. |
| verification_result | object | Overall conclusion on citation support, based on the claims, evidence, and their qualifications. |
| claim_evidence_links | array | Associations between each advertising claim and relevant evidence excerpts, including whether the evidence supports the figures, periods, conditions, and limitations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

