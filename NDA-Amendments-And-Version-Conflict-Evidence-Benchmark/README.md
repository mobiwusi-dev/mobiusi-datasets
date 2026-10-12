---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: NDA Amendments and Version Conflict Evidence Benchmark
---

# NDA Amendments and Version Conflict Evidence Benchmark

This benchmark covers original non-disclosure agreement text, amendments, clauses from different versions, and claims about current obligations, terms, or clause content. It includes cases involving unclear version relationships, incomplete amendment histories, and conflicting clauses, with labels indicating whether the available documents sufficiently support each claim and explaining the basis for that judgment. It supports the training and evaluation of legal document verifiers, particularly their ability to identify version issues, assess evidentiary sufficiency, and explain their conclusions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence_basis | array | Lists the clauses, documents, or version clues supporting the verification outcome. Entries may include clause numbers and relevant excerpts. |
| reasoning_summary | string | Explains how the document contents, version relationships, and clause conflicts support the verification outcome. |
| verification_claim | string | A claim about a current obligation, term, or clause content that must be verified against the supplied agreement materials. |
| base_agreement_text | string | The original non-disclosure agreement or the agreement text used as the starting point for comparison. |
| current_term_summary | string | Summarizes the current obligation, term, or relevant clause content that can be established from the materials, or explains why it cannot be determined. |
| identified_conflicts | array | Lists conflicts relevant to the claim among clauses in different versions or documents. This may be an empty array when no conflict is identified. |
| verification_outcome | string | A summary conclusion about the relationship between the claim and the available evidence. |
| insufficiency_reasons | array | Lists the reasons the claim cannot be sufficiently determined. This may be an empty array when the evidence is sufficient. |
| amendment_and_version_texts | string | The supplied amendments, clauses from different versions, and related version information. Multiple documents may be consolidated here with their sources noted. |
| version_relationship_status | string | Summarizes whether the relationships among the agreement versions and amendment documents can be clearly established. |
| claim_sufficiently_determined | boolean | Indicates whether the available documents are sufficient to determine the claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

