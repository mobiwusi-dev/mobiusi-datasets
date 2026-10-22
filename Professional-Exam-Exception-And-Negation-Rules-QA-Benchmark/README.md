---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Professional Exam Exception and Negation Rules QA Benchmark
---

# Professional Exam Exception and Negation Rules QA Benchmark

This benchmark focuses on exception conditions, applicability limits, and negated statements in professional exam rules. Each record provides a question, reference answer, source context, supporting evidence, and evidence location. It highlights details that can be overlooked when general rules dominate retrieval, making it useful for evaluating whether retrieval-augmented generation systems can find the relevant provisions and answer accurately based on the source.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | The professional exam question to be answered. |
| gold_answer | string | The correct answer grounded in the source context. |
| rule_feature | string | The primary rule detail tested by the question. |
| evidence_quote | string | The exact source wording that supports the answer, including any relevant exception, limitation, or negation. |
| source_context | string | The source rule or passage needed to answer the question. |
| evidence_location | string | A locator for the supporting evidence, such as a document title, article, section, page, or paragraph. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

