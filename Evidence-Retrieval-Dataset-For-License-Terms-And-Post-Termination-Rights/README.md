---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Evidence Retrieval Dataset for License Terms and Post-Termination Rights
---

# Evidence Retrieval Dataset for License Terms and Post-Termination Rights

This dataset focuses on terms, renewal conditions, termination events, and notice requirements in licensing agreements, as well as inventory disposition, rights reversion, and continuing obligations after termination. Each example connects a retrieval query with an excerpt from a legal document, supporting evidence, and a grounded conclusion, with relevant contract details represented in structured fields. It is designed to train and evaluate models that retrieve legal evidence, extract contract timelines, and analyze the consequences of license termination.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query | string | The question or information request to be answered using the legal document. |
| effective_date | string | The date on which the license or relevant contractual term takes effect, if stated. |
| source_excerpt | string | The original passage from a legal document provided as evidence for the retrieval task. |
| expiration_date | string | The stated expiration date or a date derived from the contract term, if determinable. |
| renewal_conditions | array | Conditions, deadlines, and procedures that apply to renewal or extension of the license. |
| termination_events | array | Events or circumstances that permit or trigger termination of the license. |
| notice_requirements | string | Required notice periods, delivery methods, recipients, or other conditions for renewal or termination notices. |
| contract_term_summary | string | A concise summary of the license term, including any stated start date, duration, or end conditions. |
| supporting_conclusion | string | A concise answer to the retrieval query grounded in the cited legal document excerpts. |
| post_termination_rights | string | Rights, duties, or restrictions that continue or apply after the license terminates. |
| rights_reversion_status | string | Whether and how licensed rights revert to the licensor or another party after termination, including any stated conditions. |
| supporting_evidence_quotes | array | Verbatim excerpts from legal documents that support the extracted conclusions. |
| post_termination_inventory_disposition | string | The required treatment of existing inventory after termination, such as sell-off rights, destruction, return, or a sell-off period. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

