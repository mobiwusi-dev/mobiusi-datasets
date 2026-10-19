---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Promotional Voucher Eligibility Question Answer Dataset
---

# Promotional Voucher Eligibility Question Answer Dataset

This dataset organizes campaign terms and user questions about promotional vouchers, discount codes, and special offers in question-answer records. Topics include eligible products, minimum spend requirements, exclusions, offer stacking rules, and validity periods; records can also include an eligibility status, applicable scope, a terms-based evidence excerpt, and a direct answer. It supports structured retrieval and verification of voucher restrictions, and is suitable for building or evaluating retrieval-augmented generation systems, voucher rule assistants, and e-commerce customer service applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A clear, easy-to-understand response to the user's question that is consistent with the campaign terms. |
| user_question | string | The original question about eligible products, minimum spend, exclusions, stacking rules, validity periods, or other voucher conditions. |
| campaign_terms | string | The original promotional voucher, discount code, or special offer terms used to determine eligibility. |
| evidence_quote | string | A quotation or accurate paraphrase of the campaign terms supporting the eligibility decision and answer. |
| stacking_rules | string | Whether the voucher can be combined with other offers, discounts, or promotions; state when the terms do not specify this. |
| validity_period | string | The voucher's valid dates, available usage times, or other time restrictions; state when the terms do not specify them. |
| applicable_scope | string | A summary of eligible products, categories, stores, channels, or user groups; state when the available information is insufficient. |
| eligibility_status | string | The eligibility status determined from the campaign terms; mark as insufficient information when the terms do not provide enough detail. |
| exclusion_conditions | string | Products, categories, stores, channels, or other conditions excluded from the offer; state when no explicit exclusions are specified. |
| minimum_spend_condition | string | The minimum purchase amount required to use the voucher and how the amount is calculated; state when the terms do not specify one. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

