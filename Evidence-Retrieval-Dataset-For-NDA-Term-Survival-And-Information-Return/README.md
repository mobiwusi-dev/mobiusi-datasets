---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Evidence Retrieval Dataset for NDA Term, Survival, and Information Return
---

# Evidence Retrieval Dataset for NDA Term, Survival, and Information Return

This dataset organizes evidence from non-disclosure agreement clauses covering agreement effective and termination periods, the survival of confidentiality obligations, post-termination return or destruction of information, backup retention, and written certification requirements. It links source clauses to lifecycle obligation summaries, evidence spans, evidence coverage, and performance-related retrieval queries, supporting the development and evaluation of retrieval-augmented generation systems grounded in legal text.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_text | string | Original clause text from an NDA or related material, provided as the source for identifying lifecycle obligations and locating evidence. |
| agreement_term | object | Effective date, termination, and duration information extracted from the source evidence text. |
| evidence_spans | array | Text spans located in the source evidence and linked to specific performance conclusions. |
| ambiguity_flags | array | Flags ambiguities, omissions, or conflicts in term commencement, survival scope, backup exceptions, or certification requirements that may affect performance assessments. |
| backup_retention | object | Clause information on whether backups, disaster recovery copies, automatic archives, or system copies may be retained after termination and what restrictions apply. |
| evidence_coverage | object | Indicates whether the source evidence clearly supports conclusions about each type of lifecycle obligation. |
| retrieval_queries | array | Queries generated from clause content for retrieving answers to NDA lifecycle performance questions. |
| written_certification | object | Clause information on written confirmation after return, destruction, or deletion, including its required contents, issuing party, and submission deadline. |
| confidentiality_survival | object | The duration, triggering conditions, and scope of confidentiality obligations after agreement termination, expiry, or disclosure, as identified from the agreement. |
| lifecycle_obligation_summary | string | A combined summary of performance requirements from agreement commencement and duration through post-termination return, destruction, backup retention, and written certification. |
| post_termination_information_disposition | object | Obligations to return, destroy, delete, or continue retaining confidential information after termination or expiry of the agreement, or completion of the disclosure purpose. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

