---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: University Technology Transfer License Agreement QA Dataset
---

# University Technology Transfer License Agreement QA Dataset

This dataset focuses on technology transfer license agreements used by universities and research institutions. Topics include background intellectual property, research results, commercialization obligations, diligent development, sublicensing, invention disclosures, revenue sharing, and rights after termination. Records pair contract text with questions, expert answers, supporting clauses, categorized issues, key contract elements, and human-review flags, supporting legal QA training, clause analysis, and domain-specific evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | A professional answer based on the contract text and question, accurately explaining the contractual terms and their legal or commercial implications. |
| contract_text | string | The full text, relevant clauses, or excerpts from a technology transfer license agreement used as the basis for the question and answer. |
| question_text | string | A specific legal, commercialization, or rights-related question about the technology transfer license agreement. |
| question_category | string | The contract topic addressed by the question, such as background intellectual property, research results, commercialization obligations, diligent development, sublicensing, invention disclosure, revenue sharing, or post-termination rights. |
| supporting_clause | string | Contract text, a clause summary, or a reference to the relevant contract location that supports the answer. |
| requires_human_review | boolean | Indicates whether the answer may require further professional review because the contract language is ambiguous, facts are insufficient, or expert judgment is needed. |
| relevant_contract_elements | array | Key parties, technical results, rights and obligations, terms, territories, fees, revenue-sharing provisions, or other elements extracted from the contract that are relevant to the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

