---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Social Media Comparative Advertising Fact-Checking Dataset
---

# Social Media Comparative Advertising Fact-Checking Dataset

This synthetic text dataset covers comparative claims in social media ads, including competitor comparisons, market rankings, performance advantages, and price advantages. Each record includes the claim, comparison target and dimension, qualifying conditions, evidence basis, fact-check label, and supporting analysis. It supports fact-checking model training and evaluation, advertising review, and marketing claim risk analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The original comparative claim in the social media advertisement that is to be checked. |
| risk_flags | string | Potential risks identified in the claim, such as absolute wording, missing time limits, incomparable evidence, or incomplete pricing conditions. |
| is_supported | boolean | A binary support judgment inferred from the evidence and qualifying conditions; true only when the claim as a whole is sufficiently supported. |
| claim_category | string | The normalized type assigned to the ad claim based on its content. |
| evidence_basis | string | A description of the research, statistics, pricing information, market reports, test results, or other evidence used to support or challenge the claim. |
| fact_check_label | string | The original fact-check label indicating whether the ad claim is supported by the evidence. |
| comparison_target | string | The competitor, brand, product, or service being compared in the ad claim. |
| normalized_relation | string | A normalized description of the relationship between the primary brand and the comparison target, extracted from the ad claim. |
| comparison_dimension | string | The dimension addressed by the claim, such as market ranking, performance, price, product capability, or service quality. |
| condition_consistency | string | Whether the claim's scope aligns with the time, location, sample, or scenario covered by the evidence. |
| qualifying_conditions | string | Time, location, sample, usage scenario, product version, or other limits that affect the scope in which the claim may hold. |
| evidence_support_level | string | The strength of support inferred from the evidence basis and qualifying conditions. |
| fact_check_explanation | string | An explanation of the verdict based on the comparison target, comparison dimension, qualifying conditions, and evidence basis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

