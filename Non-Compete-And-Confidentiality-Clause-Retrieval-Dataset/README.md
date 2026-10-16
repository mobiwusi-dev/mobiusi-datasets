---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Non-Compete and Confidentiality Clause Retrieval Dataset
---

# Non-Compete and Confidentiality Clause Retrieval Dataset

This dataset covers restrictive provisions in employment contracts and related agreements, including confidentiality, intellectual property ownership, non-compete, non-solicitation, and anti-poaching clauses. Annotations capture clause categories, applicable parties, restriction scope, duration, exceptions, remedies, and related details, with retrieval questions linked to supporting clauses and evidence spans. It supports building and evaluating RAG systems for precise retrieval from employment-related legal documents, including clause localization, information extraction, and compliance review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| exceptions | array | Circumstances explicitly excluded from the clause, exempted, or made inapplicable under specified conditions. |
| source_record | object | The unnormalized clause and its source context, provided as the original input for this record. |
| clause_summary | string | A concise Chinese-language summary of the restricted parties, conduct, duration, exceptions, and remedies. |
| duration_terms | object | Extracted duration, start and end conditions, and whether the restrictive obligation is open-ended. |
| evidence_spans | array | Key text spans extracted from the source clause or context to support the classification and annotations. |
| retrieval_tags | array | Standardized tags for RAG retrieval, filtering, and reranking. |
| risk_assessment | object | Identifies content that may create high-risk retrieval, legal interpretation, or semantic ambiguity. |
| clause_categories | array | One or more categories of restrictive provisions identified from the clause content. |
| restriction_scope | object | Structured extraction of confidential information, intellectual property, prohibited conduct, and geographic or industry limits. |
| applicable_subjects | array | Individuals, organizations, or other parties explicitly bound by or covered by the clause. |
| primary_clause_type | string | The main legal or business function assigned to the clause. |
| issue_correspondence | object | Links a user's retrieval query to the restriction type, key concepts, and supporting provisions in the clause. |
| compensation_and_remedies | object | Structured summary of non-compete compensation, liquidated damages, damages, and other available remedies. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

