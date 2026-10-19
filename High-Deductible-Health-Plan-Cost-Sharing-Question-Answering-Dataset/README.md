---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: High-Deductible Health Plan Cost-Sharing Question Answering Dataset
---

# High-Deductible Health Plan Cost-Sharing Question Answering Dataset

This dataset covers deductibles, coinsurance, copayments, and out-of-pocket maximums in high-deductible health plans through plan terms, care scenarios, and cost-related questions and answers. Each example requires applying plan provisions to a specific care scenario and includes a step-by-step explanation of the resulting cost-sharing treatment. It supports training and evaluation of models that interpret insurance terms, answer healthcare cost questions, and perform multi-hop cost reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct response explaining the applicable cost-sharing outcome for the scenario. |
| reasoning | string | A step-by-step explanation connecting plan provisions to the scenario and resulting cost-sharing treatment. |
| care_scenario | string | The patient's care situation, including relevant services, timing, and any stated costs or coverage details. |
| cost_question | string | A question about how plan terms apply to the care scenario and what costs the patient may owe. |
| plan_document | string | Source plan text containing relevant deductible, copayment, coinsurance, and out-of-pocket maximum provisions. |
| cost_breakdown | object | A structured summary of calculated cost-sharing amounts when supported by the source information. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

