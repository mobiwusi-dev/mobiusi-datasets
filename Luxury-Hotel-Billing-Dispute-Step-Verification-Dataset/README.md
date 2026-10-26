---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Luxury Hotel Billing Dispute Step Verification Dataset
---

# Luxury Hotel Billing Dispute Step Verification Dataset

This dataset covers guest prompts about room rates, incidental charges, and other billing items, alongside proposed hotel billing-service responses for evaluation. Responses are segmented into steps, with step-level and overall compliance labels based on billing details, authorization scope, privacy requirements, and service policies; examples focus on cases where constraints are not met. The data supports process verifier training and evaluation, helping identify erroneous steps and compliance risks in billing communications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| guest_prompt | string | The guest's question or concern about room charges, incidental expenses, or another billing item, including any provided billing context and applicable constraints. |
| response_steps | array | The candidate response segmented into steps, with each step annotated for compliance with relevant billing, authorization, privacy, and service-policy constraints. |
| candidate_response | string | The complete proposed hotel billing-service response to be evaluated, before step extraction and verification. |
| overall_assessment | string | A concise explanation of the overall verification judgment, highlighting any material step-level compliance failures. |
| overall_compliance_status | string | The overall judgment of whether the candidate response complies with the constraints across its steps. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

