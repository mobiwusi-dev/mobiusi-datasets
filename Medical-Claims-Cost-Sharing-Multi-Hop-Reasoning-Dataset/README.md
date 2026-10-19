---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Medical Claims Cost-Sharing Multi-Hop Reasoning Dataset
---

# Medical Claims Cost-Sharing Multi-Hop Reasoning Dataset

This dataset contains medical claim scenarios and questions involving deductibles, copayments, coinsurance rates, plan limits, and prior accumulations. Each example provides the patient responsibility amount, insurer payment amount, and a step-by-step explanation, supporting models that must combine multiple plan rules to calculate cost sharing. It is suitable for medical claims processing, coverage verification, and reasoning-oriented supervised fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | The original question asking for claim payment responsibility or cost-sharing amounts. |
| reasoning | string | A step-by-step explanation of the applicable deductible, copayment, coinsurance, plan limits, prior accumulations, and how they determine the amounts owed. |
| claim_case | string | The original text describing the medical claim, plan terms, limits, and any prior accumulations. |
| insurer_payment_amount | number | The calculated amount payable by the insurer, expressed in the currency used in the claim scenario. |
| patient_responsibility_amount | number | The calculated amount the patient must pay, expressed in the currency used in the claim scenario. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

