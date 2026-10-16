---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Renewal and Rent Adjustment Evidence Retrieval Benchmark
---

# Lease Renewal and Rent Adjustment Evidence Retrieval Benchmark

This benchmark covers lease provisions concerning fixed-term expiration, automatic renewal, renewal options, rent escalation, market rent review, and rent adjustment procedures. Its examples pair retrieval questions with supporting contract excerpts, testing whether systems can distinguish similar clauses, connect conditions across passages, and return complete, citable evidence. It is designed for developing, validating, and comparing retrieval-augmented generation systems for legal documents.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_summary | string | A concise conclusion that directly answers the retrieval query based on all relevant evidence. |
| evidence_spans | array | One or more original contract passages supporting the retrieval conclusion, suitable for direct quotation and traceable to the source. |
| retrieval_query | string | A question about renewal, rent adjustment, or related procedures that must be answered using the contract text. |
| source_document | string | The full text of the lease or relevant contract provisions to be searched; the original text source for evidence extraction. |
| renewal_analysis | object | An evidence-based summary of renewal arrangements, such as fixed-term expiration, automatic renewal, or renewal options. |
| evidence_completeness | object | A derived assessment of whether the retrieval results cover the key conditions for renewal and rent adjustment. |
| rent_adjustment_terms | object | An evidence-based summary of rent escalation, market rent review, and rent adjustment procedures. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

