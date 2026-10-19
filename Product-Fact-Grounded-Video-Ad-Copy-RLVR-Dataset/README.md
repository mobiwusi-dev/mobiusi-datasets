---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Product-Fact-Grounded Video Ad Copy RLVR Dataset
---

# Product-Fact-Grounded Video Ad Copy RLVR Dataset

This dataset contains synthetic product materials, permitted facts, copywriting instructions, and video ad copy intended for voiceovers or on-screen text. Structured fields capture required-fact retention, factual support for atomic claims, and verifiable reward components, enabling evaluation of key-information coverage and unsupported product claims while supporting controlled text generation and RLVR training.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| copy_format | string | Indicates whether the generated content is for a video voiceover or on-screen text. |
| total_reward | number | The overall RLVR reward score aggregated from the reward rules. |
| atomic_claims | array | Product claims extracted from the generated copy, with the factual support status of each claim. |
| generated_copy | string | Video voiceover or on-screen copy generated from the product materials, permitted facts, and instruction. |
| permitted_facts | array | Facts allowed in the copy, with an indication of whether each fact is required. |
| reward_breakdown | object | Verifiable reward components for RLVR training, with each score normalized to a range from 0 to 1. |
| product_materials | object | Synthetic product information used as source material for generating copy. |
| verification_passed | boolean | The verification outcome based on required-fact retention and unsupported-claim checks. |
| required_fact_checks | array | Checks whether each fact marked as required is expressed in the generated copy. |
| generation_instruction | string | The original instruction specifying the copy objective, constraints, style, or other generation requirements. |
| unsupported_claim_count | integer | The number of product claims in the generated copy that cannot be supported by the permitted facts. |
| required_fact_retention_rate | number | The proportion of required facts retained in the copy, ranging from 0 to 1. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

