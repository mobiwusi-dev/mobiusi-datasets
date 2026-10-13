---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Social Advertising Citation Completeness Dataset
---

# Social Advertising Citation Completeness Dataset

This dataset contains synthetic social media advertisements with multiple factual claims, together with structured annotations for reference materials, claim-to-citation mappings, missing citations, and evidence-chain analysis. It focuses on whether important claims have appropriate citations and whether the support chain from each claim to specific evidence is complete. The data supports training and evaluating citation verification, fact-checking, and content moderation systems for advertising.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| fact_claims | array | Verifiable factual claims identified in the advertisement, including their importance and citation requirements. |
| coverage_summary | object | A summary of citation coverage and completeness across the advertisement's factual claims. |
| missing_citations | array | Key factual claims identified as lacking required citation support or a corresponding citation. |
| advertisement_text | string | The complete synthetic social media advertisement text to be analyzed. |
| reference_materials | array | A collection of sources that the advertisement may cite or that can be used to verify its claims. |
| claim_citation_mappings | array | The relationships between each factual claim and the references provided or matched in the advertisement, including the degree of support. |
| evidence_chain_analysis | array | An assessment of whether the support chain from a factual claim to its cited source and specific evidence excerpt is complete. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

