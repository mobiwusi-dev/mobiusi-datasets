---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mobile Banking Product and Service Policy Summarization Dataset
---

# Mobile Banking Product and Service Policy Summarization Dataset

This dataset pairs long-form mobile banking product descriptions, service rules, and related policy documents with summaries of their applicability scope, key conditions, user action requirements, and exceptions. It focuses on covered users and services, eligibility requirements, limitations, and special cases, supporting models that summarize policy documents and extract key information in a structured format. It is suitable for financial text processing, customer support knowledge development, and domain-specific model fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| exceptions | string | A summary of exclusions, special cases, limitations, and circumstances in which the standard policy does not apply. |
| key_conditions | string | A summary of eligibility requirements, limits, fees, timing rules, and other conditions users must meet. |
| applicability_scope | string | A summary of the users, accounts, products, services, regions, or situations covered by the policy. |
| source_document_text | string | The complete original mobile banking product description, service rules, or policy text. |
| user_action_requirements | string | A summary of the steps, information, confirmations, or precautions required of the user. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

