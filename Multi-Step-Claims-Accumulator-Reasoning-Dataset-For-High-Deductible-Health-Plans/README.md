---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Step Claims Accumulator Reasoning Dataset for High-Deductible Health Plans
---

# Multi-Step Claims Accumulator Reasoning Dataset for High-Deductible Health Plans

This dataset presents chronological high-deductible health plan rules, prior claims, and current claim scenarios, covering deductibles, coinsurance, copays, and annual out-of-pocket maximums. Each example combines plan rules and accumulated amounts to derive the deductible applied to the current claim, the patient's cost share, and the out-of-pocket limit status, with reasoning steps and a final answer. It supports health insurance claims analysis, benefit calculations, and the training and evaluation of reasoning-focused language models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | The direct answer to the reasoning question, including relevant calculated amounts and accumulator status. |
| prior_claims | string | Source text listing claims earlier in the plan year and their effects on deductible and out-of-pocket accumulators. |
| current_claim | string | Source text describing the current covered service, its allowed expense, and any relevant claim details. |
| plan_year_rules | string | Source text describing the plan-year deductible, coinsurance, copay, and out-of-pocket maximum rules. |
| reasoning_steps | string | A concise, ordered explanation of how prior accumulators and current claim expenses determine the calculation. |
| reasoning_question | string | The question to answer using the plan rules, prior claims, and current claim information. |
| applicable_cost_sharing | string | The cost-sharing rule applied to the current claim, such as a copay or a patient and plan coinsurance split. |
| total_patient_responsibility | number | The patient's total responsibility for the current claim after applying the deductible, cost sharing, and out-of-pocket maximum rules, in the currency units used by the input. |
| out_of_pocket_maximum_reached | boolean | Whether the plan-year out-of-pocket maximum has been reached after processing the current claim. |
| out_of_pocket_maximum_remaining | number | The amount remaining before the plan-year out-of-pocket maximum is reached, after processing the current claim, in the currency units used by the input. |
| deductible_remaining_after_claim | number | The deductible amount remaining after processing the current claim, in the currency units used by the input. |
| deductible_applied_to_current_claim | number | The amount of the current claim applied to the deductible, in the currency units used by the input. |
| patient_cost_share_after_deductible | number | The patient's cost share on the allowed amount remaining after the deductible, in the currency units used by the input. |
| out_of_pocket_accumulated_after_claim | number | The plan-year out-of-pocket accumulator after processing the current claim, in the currency units used by the input. |
| remaining_allowed_amount_after_deductible | number | The current claim's allowed amount remaining after the deductible portion is applied, in the currency units used by the input. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

