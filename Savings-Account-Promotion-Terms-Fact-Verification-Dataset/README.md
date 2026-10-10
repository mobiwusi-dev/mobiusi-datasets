---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Savings Account Promotion Terms Fact Verification Dataset
---

# Savings Account Promotion Terms Fact Verification Dataset

This dataset focuses on webpage text about savings account sign-up bonuses, limited-time offers, and promotional interest rates. Each example includes a claim to verify, a claim category, evidence text, a judgment, and an explanation, covering details such as eligibility, qualifying deposits, holding periods, deadlines, and reward payment rules. It supports fact verification model training and evaluation, as well as financial product term analysis and promotion review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| judgment | string | The fact verification conclusion reached for the claim based on the webpage evidence. |
| evidence_text | string | A relevant passage selected from the promotional webpage text to support or refute the claim. |
| claim_category | string | The category of promotion terms inferred from the content of the claim. |
| claim_statement | string | A claim to verify about promotion eligibility, qualifying deposits, holding periods, deadlines, reward payment rules, or promotional interest rates. |
| source_page_text | string | Original text from a webpage about a savings account sign-up bonus, limited-time offer, or promotional interest rate. |
| judgment_explanation | string | An explanation of how the evidence supports or refutes the claim, or why the available evidence is insufficient to reach a conclusion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

