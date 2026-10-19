---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Leveraged Loan Credit Agreement Summarization Dataset
---

# Leveraged Loan Credit Agreement Summarization Dataset

This dataset pairs long-form leveraged loan credit agreements with professional summaries covering facility amounts and borrowing mechanics, pricing, maturity and repayment, financial covenants, restrictive covenants, waivers and amendments, and events of default. Its structured content helps users identify material provisions affecting lender rights and borrower obligations for financial legal analysis, agreement review, and domain-specific model training. Designed for domain expert supervised fine-tuning, it supports concise, focused summarization of complex financing documents.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| pricing_terms | string | Summary of interest rates, margins, benchmark rates, floors, fees, payment frequency, and applicable pricing adjustments. |
| agreement_text | string | Full text of the leveraged loan credit agreement used as the source for summarization. |
| events_of_default | string | Summary of events of default, relevant thresholds and grace periods, and any resulting acceleration or enforcement rights. |
| financial_covenants | string | Summary of financial maintenance or incurrence covenants, calculation methods, testing dates, thresholds, and related cure rights. |
| loan_facility_terms | string | Summary of the facilities, commitments, loan amounts, currencies, permitted uses, and borrowing mechanics. |
| professional_summary | string | Concise expert summary of the agreement that preserves material terms affecting lender rights and borrower obligations. |
| restrictive_covenants | string | Summary of restrictions on indebtedness, liens, investments, asset sales, distributions, mergers, and other material activities, including exceptions and baskets. |
| waivers_and_amendments | string | Summary of waivers, amendments, consents, affected provisions, applicable conditions, and any changes to rights or obligations. |
| maturity_and_repayment_terms | string | Summary of maturity dates, repayment schedules, amortization, prepayments, and other repayment obligations. |
| lender_rights_and_borrower_obligations | string | Summary of material lender protections, remedies, consent rights, reporting duties, and borrower obligations not otherwise adequately captured above. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

