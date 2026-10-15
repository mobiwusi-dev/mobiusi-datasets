---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Copyright and Publishing License Contract Q&A Dataset
---

# Copyright and Publishing License Contract Q&A Dataset

This dataset contains questions and answers about copyright and publishing license documents for books, film and television, images, and digital content. Topics include rights types, media formats, distribution territories, adaptation rights, attribution, royalty settlements, rights reversion, and content delivery, with contract evidence and summaries that help trace the basis and conditions for each answer. It supports domain-specific supervised fine-tuning, closed-domain legal question answering, and contract clause comprehension evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A domain-specific answer based on contract clauses or document content that directly addresses the question and explains applicable conditions. |
| question | string | A question extracted from the source contract Q&A text, focused on specific facts or rules concerning copyright or publishing license agreements. |
| source_text | string | Unstructured source text from contract clauses, questions, answers, or related documents that serves as the input for this record. |
| contract_scope | object | Information summarized from the contract Q&A about covered work types, work titles, media formats, and distribution territories. |
| rights_analysis | object | A structured summary of the copyright rights granted by the contract, including adaptation rights, attribution requirements, and exclusivity. |
| commercial_terms | object | A summary of commercial contract terms, including royalties, license fees, settlement periods, and settlement conditions. |
| evidence_clauses | array | Excerpts from the contract and their location details that support the answer and structured conclusions. |
| answer_basis_summary | string | A concise summary of the key contract clauses, applicable rights scope, and limitations supporting the answer. |
| delivery_and_reversion | object | Structured details on content and asset delivery, deadlines, triggers for rights reversion, and reversion status. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

