---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Sports News Claim Verification Dataset
---

# Sports News Claim Verification Dataset

This dataset contains verifiable factual claims extracted from sports news webpages, webpage text used to assess those claims, and verification labels indicating whether the evidence supports, refutes, or is insufficient to decide. It also marks the locations of relevant evidence in the webpage text, linking news claims to their textual basis. It is suited to automated evaluation of fact verification models, evidence localization research, and the development of sports news fact-checking workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The factual claim extracted from a sports news article. |
| evidence_spans | array | The locations and quoted text of relevant evidence within the evidence page text. |
| evidence_page_text | string | The webpage text used as evidence to assess the claim. |
| verification_label | string | The assessment of whether the webpage evidence supports or refutes the claim, or is insufficient to decide. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

