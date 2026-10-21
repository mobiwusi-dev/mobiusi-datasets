---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Term Deposit Product Fact Verification Dataset
---

# Term Deposit Product Fact Verification Dataset

This dataset pairs factual claims from term deposit product pages published by banks and other deposit-taking institutions with supporting webpage evidence. It covers product attributes such as interest rates, deposit terms, minimum deposit amounts, and maturity handling, with records linking claims to source content, URLs, institution and product details, verification outcomes, and supporting rationale. Use it to train and evaluate models that verify financial product information against web text, retrieve evidence, and explain their conclusions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The original factual claim about a term deposit product attribute, such as its interest rate, term, or minimum deposit amount. |
| page_value | string | The relevant product attribute value extracted from the webpage evidence; left blank when the page provides no verifiable value. |
| webpage_url | string | The URL of the webpage containing product information and verification evidence. |
| product_name | string | The term deposit product identified from the claim or webpage content. |
| claimed_value | string | The specific product attribute value extracted from the claim, preserving its original wording and units. |
| fact_category | string | The category of term deposit product attribute addressed by the claim. |
| evidence_quote | string | A verbatim excerpt from the webpage that supports or refutes the claim, or helps determine that the evidence is insufficient. |
| webpage_content | string | The original content of a bank or other deposit-taking institution webpage used to verify the claim, with HTML text preserved. |
| evidence_context | string | Webpage text describing where the evidence excerpt appears or providing relevant surrounding context. |
| institution_name | string | The bank or other deposit-taking institution identified from the claim or webpage content. |
| verification_result | string | The conclusion reached about the claim based on the webpage evidence. |
| verification_rationale | string | An explanation of why the webpage evidence supports or refutes the claim, or why it is insufficient to reach a conclusion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

