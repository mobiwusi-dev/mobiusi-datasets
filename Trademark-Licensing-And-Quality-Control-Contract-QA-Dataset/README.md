---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Trademark Licensing and Quality Control Contract QA Dataset
---

# Trademark Licensing and Quality Control Contract QA Dataset

This dataset provides document-based question answering examples drawn from trademark license agreements and related clauses. Topics include trademark usage requirements, quality control, brand approval, territorial scope, licensee obligations, infringement notices, and license termination. Each example can include the contract text, a question, a contract-grounded answer, supporting evidence, extracted rules, and a topic label, supporting legal document QA, clause analysis, rule extraction, and evidence verification.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate, complete, document-based response to the question, grounded in the contract text. |
| question | string | A question about trademark usage requirements, quality control, brand approval, territory, licensee obligations, infringement notices, or license termination. |
| answer_basis | array | Contract clauses, source-text excerpts, or clause locations that support the answer. |
| contract_text | string | Original text of a trademark license agreement or related contract clauses. |
| question_focus | string | The trademark license agreement topic category inferred from the question. |
| extracted_rules | object | Structured rules extracted from the contract concerning trademark authorization, usage restrictions, and quality control. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

