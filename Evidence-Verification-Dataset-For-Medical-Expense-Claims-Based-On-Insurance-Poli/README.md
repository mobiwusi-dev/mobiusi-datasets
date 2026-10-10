---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Evidence Verification Dataset for Medical Expense Claims Based on Insurance Policies and Contracts
---

# Evidence Verification Dataset for Medical Expense Claims Based on Insurance Policies and Contracts

Designed for medical expense claims, this dataset pairs insurance contracts, policy wording, endorsements, and other legal documents with claim requirements to verify whether the documents support specific expenses or coverage conditions. Annotations cover policy version alignment, applicable conditions, supporting evidence spans, and conflicts between documents. The data supports training and evaluating claims evidence verifiers, as well as assisting claims review and legal document analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| support_level | string | The overall degree to which the source documents support the claim requirement being verified. |
| evidence_spans | array | Document clauses or source passages used in the judgment, with their relationship to the claim requirement. |
| version_alignment | string | Whether the cited policy wording version applies to the relevant policy and claim. |
| decision_rationale | string | A concise explanation of the overall judgment based on the evidence spans, version alignment, and applicable conditions. |
| document_conflicts | array | Relevant conflicts between contracts, policy wording, endorsements, or other documents. Use an empty array when no conflicts are identified. |
| condition_assessment | string | Whether the conditions specified in the documents are met, missing, or contradicted by the available information. |
| source_documents_text | string | Text of source documents such as insurance contracts, policy wording, and endorsements. Clearly separate multiple documents and retain their names, versions, and clause details. |
| claim_requirement_text | string | The medical expense item, coverage condition, or specific claim assertion that needs verification. |
| missing_or_unmet_conditions | array | Conditions required by the documents that the available claim information does not establish as met, or that are explicitly unmet. Use an empty array when there are none. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

