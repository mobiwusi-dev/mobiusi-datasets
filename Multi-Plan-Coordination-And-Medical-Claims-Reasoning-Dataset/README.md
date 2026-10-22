---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Plan Coordination and Medical Claims Reasoning Dataset
---

# Multi-Plan Coordination and Medical Claims Reasoning Dataset

This dataset is built around medical claim case text covering multiple patient coverage plans, coordination rules, claim amounts, prior payments, pending charges, and related questions. Cases are represented with structured fields for coverage plans, payment order, processable amounts, reasoning steps, and answers. Models use plan rules and case facts to infer claim-processing order or calculate the amount available to the next plan, supporting multi-hop question answering, reasoning fine-tuning, and business logic evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | Direct answer to the claim-processing question, including the applicable processing order or amount. |
| claim_amount | number | Total claim or billed amount, when provided in the case. |
| currency_code | string | Currency used for the claim and payment amounts, when stated or inferable from the case. |
| payment_order | array | Sequence in which the coverage plans should process the claim. |
| coverage_plans | array | Coverage plans identified in the case, including relevant rules and payment facts. |
| pending_amount | number | Claim amount that remains unpaid or is available for further processing, based on the case facts. |
| reasoning_steps | array | Ordered explanation connecting plan rules and case facts to the payment order or amount calculation. |
| source_case_text | string | Original case text containing the patient's coverage plans, coordination rules, claim facts, and question. |
| processable_amount | number | Amount available for submission to or consideration by the next plan, based on the claim balance and prior payments. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

