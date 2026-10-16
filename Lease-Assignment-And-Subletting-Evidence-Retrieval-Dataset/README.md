---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Assignment and Subletting Evidence Retrieval Dataset
---

# Lease Assignment and Subletting Evidence Retrieval Dataset

Focused on lease assignment, subletting, consent requirements, prohibitions, assignee obligations, and changes of control, this dataset pairs lease text and relevant definitions with retrieval questions and locatable contractual evidence. Structured judgment and legal basis summaries help models connect conclusions to source clauses; coverage centers on these lease provisions, while the specific sample count is stated on the product page. It supports lease review, legal evidence retrieval, and grounding for training or evaluating lease-focused RAG systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| contract_text | string | Text of the lease agreement to be searched, including relevant definitions contained in the agreement. |
| evidence_items | array | Source text retrieved from the contract or its definitions that directly supports a judgment, together with location information. |
| retrieval_query | string | A specific question about assignment, subletting, consent requirements, allocation of obligations, or a change of control, posed against the contract text. |
| judgment_summary | object | A structured assessment of lease assignment, subletting, related obligations, and changes of control based on contractual evidence. |
| legal_basis_summary | string | A summary of the contractual provisions supporting the assignment or subletting judgment and the conditions under which they apply. |
| retrieval_confidence | number | A confidence score from 0 to 1 for the structured judgment, based on evidence completeness, clause clarity, and retrieval accuracy. |
| definition_implications | array | Specific effects of contractual definitions on assessments involving assignment, subletting, assignees, affiliates, or changes of control. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

