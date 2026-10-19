---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Leveraged Loan Amendment and Waiver Document Summarization Dataset
---

# Leveraged Loan Amendment and Waiver Document Summarization Dataset

This dataset covers long-form credit agreement amendments, covenant waivers, and related supplemental documents in leveraged lending, paired with structured summaries of key changes and their financing implications. It focuses on amended provisions, scope of applicability, effectiveness conditions, and practical effects on borrowers and lenders. The data supports training and evaluating models for complex financing document review and transaction monitoring.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| amendments | array | Material provisions changed or waived, including prior terms, revised terms, applicability, and conditions. |
| lender_impact | string | Practical consequences for lenders, including changes to rights, protections, consent requirements, and exposure. |
| amendment_types | array | Categories of amendments, waivers, or other relief granted by the document. |
| borrower_impact | string | Practical consequences for the borrower, including obligations, flexibility, restrictions, and compliance considerations. |
| financing_impact | string | Analysis of material effects on facility availability, pricing, maturity, repayment, collateral, covenant protection, or other financing terms. |
| executive_summary | string | Concise summary of the principal changes and their significance to the financing. |
| interpretive_notes | string | Material ambiguities, assumptions, limitations, or points requiring verification against the underlying credit agreement or related documents. |
| source_document_text | string | Full text of the credit agreement amendment, covenant waiver, or related supplemental document being analyzed. |
| effectiveness_conditions | array | Conditions precedent and other requirements governing the effectiveness of the amendment or waiver. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

