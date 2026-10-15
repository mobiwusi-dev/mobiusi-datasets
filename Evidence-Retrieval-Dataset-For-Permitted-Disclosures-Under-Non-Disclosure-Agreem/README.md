---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Evidence Retrieval Dataset for Permitted Disclosures under Non-Disclosure Agreements
---

# Evidence Retrieval Dataset for Permitted Disclosures under Non-Disclosure Agreements

This dataset focuses on NDA provisions governing permitted recipients, the need-to-know principle, recipient confidentiality obligations, professional advisers, and affiliates. It pairs fact questions about disclosure scenarios with supporting clause evidence, covering recipients, purposes, conditions, conclusions, and reasoning. It supports evaluation of legal evidence retrieval and clause-grounded responses, as well as NDA review and retrieval-augmented generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| fact_question | string | Describes the specific disclosure, recipient, purpose, and relevant facts, and asks whether the disclosure is permitted under the NDA. |
| disclosure_target | string | Identifies the actual recipient of the confidential information based on the fact question, such as an affiliate, director, officer, employee, professional adviser, or other third party. |
| necessary_to_know | boolean | Indicates whether the recipient needs to know the confidential information to perform duties, provide professional services, or complete matters related to the agreement. |
| reasoning_summary | string | Briefly explains the legal reasoning behind the disclosure permission conclusion by combining the facts, agreement conditions, and supporting clauses. |
| source_legal_text | string | The original NDA, relevant clauses, or other legal text to be searched and used as the source of supporting evidence. |
| disclosure_purpose | string | Summarizes why the confidential information is disclosed and whether the purpose relates to a use permitted by the agreement. |
| recipient_category | string | Summarizes the recipient's identity or category under the agreement. |
| permission_conclusion | string | States whether the disclosure is permitted under the NDA, based on the fact question and supporting clauses. |
| permission_conditions | array | Lists any additional conditions required for the disclosure to be permitted, such as limiting disclosure to what is necessary, requiring recipient confidentiality obligations, or restricting the purpose. |
| supporting_clause_evidence | array | Lists agreement clauses or other legal evidence supporting the conclusion, including excerpts, clause locations, and their relevance to the fact question. |
| professional_adviser_or_affiliate | boolean | Indicates whether the recipient is a professional adviser, affiliate, or other category expressly permitted by the agreement. |
| recipient_bound_by_confidentiality | boolean | Indicates whether the recipient is subject to confidentiality obligations at least as protective as those in the original agreement, professional duties of confidentiality, or another binding confidentiality arrangement. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

