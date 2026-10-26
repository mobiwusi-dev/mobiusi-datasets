---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent License Royalty and Milestone Terms Evidence Verification Dataset
---

# Patent License Royalty and Milestone Terms Evidence Verification Dataset

This dataset uses patent license agreements, royalty schedules, amendments, and related transaction documents to assess assertions about royalty rates, calculation bases, milestone triggers, and reporting obligations. Each sample records whether the documents adequately support the claim, together with clause references, verbatim evidence excerpts, an analytical rationale, and any evidence gaps or conflicts. It supports training and evaluating legal-document verifiers that determine whether contractual statements are substantiated and locate the relevant evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_category | string | The type of contractual term addressed by the claim. |
| claim_statement | string | The transaction-term assertion to be verified against the provided source documents. |
| source_documents | array | The license agreements, royalty schedules, amendments, or related transaction documents to be evaluated. |
| analysis_rationale | string | A concise explanation connecting the cited contractual language to the claim and the evidence determination. |
| evidence_determination | string | The conclusion about whether the documents provide adequate support for the claim. |
| evidence_gaps_or_conflicts | array | Missing terms, ambiguities, or inconsistencies that limit or contradict the documentary support for the claim. |
| supporting_evidence_quotes | array | Verbatim excerpts from the source documents that support or contradict the claim. |
| supporting_clause_references | array | Clause numbers, section titles, exhibit identifiers, or other locations relevant to the determination. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

