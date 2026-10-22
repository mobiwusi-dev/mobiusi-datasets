---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Construction Payment Application Evidence Verification Dataset
---

# Construction Payment Application Evidence Verification Dataset

This dataset covers work completion claims in payment applications, contract measurement clauses, site records, and other project text evidence, with verification outcomes and issue explanations. It focuses on determining whether claims are supported by the available evidence and flagging risks such as missing measurement grounds or inconsistent records. It is suited to training and evaluating text reasoning models for construction payment review, contract compliance checks, and project controls.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| site_records | string | Raw site records relevant to the claimed work, such as inspection notes, daily reports, or measured quantities. |
| issue_summary | string | A concise summary of missing measurement grounds, contradictory records, or other identified verification issues. |
| claim_supported | boolean | Whether the supplied evidence supports the work completion claim. |
| evidence_assessment | string | A concise explanation of how the supplied evidence supports or fails to support the claim. |
| verification_status | string | Overall assessment of whether the claim is supported by the supplied evidence. |
| work_completion_claim | string | The applicant's statement describing the completed work and the quantities or amounts claimed. |
| project_textual_evidence | string | Additional project text evidence provided to evaluate the payment application claim. |
| measurement_basis_missing | boolean | Whether the evidence lacks a measurement basis needed to assess the claimed quantities or amounts. |
| contract_measurement_clause | string | Contract text specifying how the relevant work or quantities should be measured. |
| record_inconsistency_detected | boolean | Whether the supplied records contain inconsistencies relevant to the claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

