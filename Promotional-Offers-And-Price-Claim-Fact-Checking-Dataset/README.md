---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Promotional Offers and Price Claim Fact-Checking Dataset
---

# Promotional Offers and Price Claim Fact-Checking Dataset

This dataset focuses on claims in social media promotions, including discounts, original prices, limited-time offers, spend thresholds, gifts, and stock limits. Each record can pair promotional copy with evidence about timing, eligibility, inventory, prices, or campaign rules, along with verification outcomes. Extracted claim attributes, evidence status, missing requirements, expiration flags, and explanations support training and evaluation for identifying incomplete conditions, expired offers, and unsupported promotional claims.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| currency | string | The currency unit or currency code associated with the extracted price. |
| claim_type | string | The primary type of promotional claim identified in the copy. |
| gift_offer | string | A gift, add-on product, or service promised in the promotional copy. |
| is_expired | boolean | Whether the offer is expired, based on its deadline and the record context. |
| sale_price | number | The discounted price or promotional selling price extracted from the copy. |
| stock_limit | integer | An explicitly stated remaining inventory, limited quantity, or purchase limit found in the copy or evidence. |
| discount_rate | number | The discount percentage extracted from the copy, ranging from 0 to 100. |
| minimum_spend | number | The minimum purchase amount required for a spend-and-save or spend-and-get promotion. |
| is_unsupported | boolean | Whether the promotional claim lacks sufficient evidence or clearly conflicts with the evidence. |
| original_price | number | The product's original price extracted from the promotional copy; this field may be absent if no original price is stated. |
| promotion_text | string | Synthetic or collected social media promotional text containing claims about discounts, prices, deadlines, spend thresholds, gifts, or stock. |
| record_context | object | Original context for the promotion record, such as source platform, publication time, region, and currency. |
| evidence_status | string | An assessment of how strongly the available evidence supports the promotional claim. |
| confidence_score | number | The model's confidence in the extracted information and verification conclusion, ranging from 0 to 1. |
| promotion_deadline | string | The promotion end date, time, or relative deadline extracted from the copy or evidence. |
| detected_conditions | array | Applicable products, purchase quantities, membership requirements, regions, time limits, or other restrictions identified from the copy and evidence. |
| missing_requirements | array | Key conditions or supporting materials found to be unspecified in the copy or evidence during verification. |
| verification_conclusion | string | The fact-checking label assigned after considering the promotional copy and evidence about timing and conditions. |
| supporting_evidence_text | string | Evidence text about timing, eligibility, inventory, pricing, or campaign rules used to verify promotional claims. |
| verification_explanation | string | An explanation of the conclusion, including matches or conflicts involving prices, deadlines, inventory, conditions, or evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

