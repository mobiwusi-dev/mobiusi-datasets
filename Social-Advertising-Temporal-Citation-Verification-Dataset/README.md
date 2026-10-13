---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Social Advertising Temporal Citation Verification Dataset
---

# Social Advertising Temporal Citation Verification Dataset

This dataset contains synthetic social ad claims featuring time-sensitive phrases such as “latest,” “current,” “as of [date],” and “updated,” paired with evidence text that includes publication dates, validity periods, and version information. Records are organized into claim, evidence, temporal analysis, evidence-time alignment, and citation validation fields to assess whether evidence supports a claim at the time an ad is published. It supports citation checking, temporal reasoning, fact verification, and ad content review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| ad_claim_record | object | Original claim record containing time-sensitive wording and citation information from the ad. |
| evidence_record | object | Original evidence text record containing publication dates, validity periods, and version information. |
| temporal_analysis | object | Analysis of temporal sensitivity and time references inferred from the ad claim and its publication time. |
| evidence_alignment | object | Temporal consistency result based on comparing the ad publication time with evidence dates, validity periods, and version information. |
| citation_validation | object | Final assessment of citation validity based on factual content matching and temporal alignment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

