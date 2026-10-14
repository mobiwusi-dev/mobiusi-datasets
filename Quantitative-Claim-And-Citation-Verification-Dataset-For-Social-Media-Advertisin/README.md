---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Quantitative Claim and Citation Verification Dataset for Social Media Advertising
---

# Quantitative Claim and Citation Verification Dataset for Social Media Advertising

This dataset contains synthetic quantitative claims for social media ads, including percentages, statistics, averages, sample sizes, and survey results, paired with citation excerpts that may support or contradict each claim. The excerpts provide verification details such as units, denominators, time ranges, and calculation methods, enabling checks of numerical evidence, metric definitions, and applicable conditions. It is designed for training and evaluating ad content review, fact-checking, and citation verification systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The original synthetic quantitative claim from a social media advertisement that requires verification. |
| citation_text | string | The original excerpt used to support or contradict the ad claim, including verifiable details such as units, denominators, time ranges, or calculation methods. |
| claim_analysis | object | The quantitative metrics and applicable conditions extracted from the original ad claim. |
| citation_analysis | object | The numerical evidence, metric definitions, and applicable conditions extracted from the citation excerpt. |
| validation_result | object | The item-level support judgments and overall conclusion produced by comparing the ad claim with the citation excerpt. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

