---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Licensing Contract Exceptions and Ambiguous Clause QA Benchmark Dataset
---

# Licensing Contract Exceptions and Ambiguous Clause QA Benchmark Dataset

This benchmark covers challenging licensing contract excerpts involving authorization exceptions, cross-referenced definitions, conditional rights, order of precedence, conflicting clauses, and obligations that survive termination. Each excerpt is paired with a question and a text-grounded reference answer, with supporting evidence, reasoning steps, and structured clause interpretations. The dataset supports domain-specific supervised fine-tuning and evaluation focused on long-tail language, limiting conditions, and easily confused provisions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate, complete answer grounded in the contract excerpt and the question. |
| question | string | A legal or contractual interpretation question about the source text that must be answered using the text. |
| answer_type | string | Identifies the primary type of answer required by the question. |
| source_text | string | The licensing contract text or relevant context to analyze, preserving clause numbers, limiting conditions, and cross-references. |
| cited_evidence | object | Contract clause locations and excerpts supporting the answer, with their relevance to the conclusion. |
| reasoning_steps | array | Verifiable analysis steps showing how textual evidence, conditions, exceptions, and conclusions relate. |
| issue_categories | array | One or more labels identifying applicable types of challenging contract language. |
| ambiguity_analysis | object | Identifies whether a clause permits multiple reasonable interpretations and records competing readings and the basis for resolving them. |
| structured_interpretation | object | A structured representation of the rights, applicable conditions, exceptions, order of precedence, and post-termination duties discussed in the answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

