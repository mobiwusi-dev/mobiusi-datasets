---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Compensation and Benefits Clause Retrieval Dataset
---

# Compensation and Benefits Clause Retrieval Dataset

This dataset focuses on base pay, bonuses, equity incentives, commissions, employee benefits, reimbursements, and payment conditions found in employment agreements and related legal documents. It pairs retrieval questions with clause evidence and answer summaries to support queries from employees, employers, and legal professionals about compensation rights, obligations, eligibility conditions, and settlement rules. Use it to build and evaluate retrieval-augmented generation systems for employment agreements, including clause retrieval, information extraction, and evidence verification.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| risk_flags | array | Potential ambiguities, omissions, conditional restrictions, calculation disputes, or legal review risks in the clauses. |
| benefit_items | array | Employee benefits extracted from the contract, such as insurance, leave, subsidies, allowances, and other benefits. |
| contract_text | string | Original text from an employment agreement or related compensation and benefits legal document. |
| evidence_spans | array | Contract excerpts supporting answers to retrieval queries, together with source-location information. |
| retrieval_query | string | A compensation or benefits clause query posed by an employee, employer, or legal professional. |
| confidence_score | number | A score from 0 to 1 estimating the accuracy of the structured extraction and its association with clause evidence. |
| clause_categories | array | Compensation and benefits clause categories identified in the contract text. |
| currency_mentions | array | Currency names or currency codes identified in the clauses. |
| retrieval_summary | string | A concise answer to the retrieval query, generated from the supporting contract clause evidence. |
| compensation_items | array | Specific compensation items extracted from the contract, such as base pay, bonuses, equity incentives, and commissions. |
| payment_conditions | object | Contract provisions on pay frequency, payment dates and methods, deductions, and final settlement upon departure. |
| rights_obligations | array | Rights, obligations, and legal consequences concerning compensation and benefits for employees, employers, or other parties. |
| reimbursement_terms | object | Structured information about reimbursable expenses, application procedures, required documentation, and reimbursement deadlines. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

