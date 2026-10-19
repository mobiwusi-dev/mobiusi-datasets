---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Contract Document Package Evidence Sufficiency Dataset
---

# Contract Document Package Evidence Sufficiency Dataset

Designed for purchase and sales agreement workflows, this dataset covers cross-document claims involving master agreements, attachments, order documents, and amendments. Each record identifies the documents or contractual provisions needed to assess a claim, whether the supplied materials provide sufficient support, and which critical evidence may be missing. It supports training and evaluation of verifiers that reason across multiple legal documents rather than relying on an isolated clause.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The procurement or sales contract claim to be evaluated against the supplied document package. |
| evidence_findings | array | Cross-document findings that connect required evidence to supporting or conflicting material in the supplied package. |
| required_evidence | array | The documents or contractual provisions needed to substantiate the claim. |
| contract_documents | array | The source documents in the contract package, including agreements, attachments, orders, and amendments. |
| assessment_rationale | string | A concise explanation of the sufficiency decision that accounts for cross-document dependencies and does not rely solely on an isolated clause. |
| evidence_sufficiency | string | Whether the supplied package contains enough evidence to support the claim. |
| missing_critical_evidence | array | Key documents, clauses, or facts absent from the supplied package that prevent a complete evidentiary conclusion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

