---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Affordable Housing Policy and Incentives Multi-Hop QA Dataset
---

# Affordable Housing Policy and Incentives Multi-Hop QA Dataset

This dataset organizes affordable housing policy text covering eligibility conditions, income and housing requirements, development obligations, and available incentives, alongside questions, answers, conclusions, and reasoning steps that require combining multiple clauses. It supports determining whether a project meets policy conditions and deriving a potential application path or set of options. Use it to train and evaluate models for housing policy analysis, multi-hop question answering, and project eligibility assessment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A clear conclusion or direct response to the question. |
| question | string | A housing policy question that requires combining multiple clauses in the policy text. |
| policy_text | string | Original housing policy text used as the basis for reasoning, including eligibility conditions, income or housing requirements, development obligations, and incentive provisions. |
| project_path | string | A potential project application pathway or set of options derived from policy conditions, development obligations, and available incentives. |
| reasoning_steps | array | An ordered, multi-step reasoning process that combines relevant policy clauses to reach a conclusion. |
| supporting_clauses | string | Policy clauses and related information that support the answer and reasoning conclusion. |
| eligibility_conclusion | string | States whether the project meets the policy's eligibility conditions and summarizes the key factors behind the conclusion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

