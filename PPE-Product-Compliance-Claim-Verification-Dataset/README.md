---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: PPE Product Compliance Claim Verification Dataset
---

# PPE Product Compliance Claim Verification Dataset

This dataset focuses on compliance and protective-performance claims found on personal protective equipment (PPE) product pages. Examples combine product page HTML, reference source text, claims to verify, and related evidence excerpts. Fields cover claim types, cited standards or regulations, claimed protection, evidence relations, verification labels, and rationales, supporting model training and evaluation for determining whether evidence supports, contradicts, or is insufficient to establish a claim. Typical uses include PPE product review, compliance fact-checking, and web evidence analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | Compliance or protective-performance claim extracted from the product page for fact verification. |
| claim_type | string | Category assigned to the claim being verified. |
| product_name | string | Name of the personal protective equipment product extracted from the product page. |
| claimed_standard | string | Standard, regulation, or certification named in the claim; an empty string is used if none is mentioned. |
| evidence_excerpt | string | Verbatim excerpt from a reference source that is relevant to the claim being verified. |
| evidence_relation | string | Relationship between the evidence excerpt and the claim being verified. |
| product_page_html | string | Original HTML content from the product webpage, including product information and manufacturer compliance claims. |
| claimed_protection | string | Hazard, protection level, or performance metric specified in the claim; an empty string is used if none is mentioned. |
| verification_label | string | Supervised verification outcome assigned to the product compliance claim. |
| reference_source_url | string | Web address for the reference evidence; an empty string is used when the source is not a webpage or its URL cannot be identified. |
| reference_source_text | string | Original reference text used to verify a claim, from manufacturer technical materials or an applicable authoritative webpage. |
| verification_rationale | string | Brief explanation of how the evidence supports or contradicts the claim, or why it is insufficient to reach a conclusion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

