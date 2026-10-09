---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Scaffolding Design and Load Specification Document Understanding Benchmark
---

# Scaffolding Design and Load Specification Document Understanding Benchmark

This benchmark focuses on web text covering scaffolding design guidance, load classifications, and configuration restrictions. Its questions test whether a model can interpret relationships among numerical conditions, applicable configurations, and limitations using the source text. Each record includes a source document, question, reference answer, supporting evidence, and a summary of constraint relationships, making it useful for evaluating document understanding and evidence-based responses rather than standalone numerical calculation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | A question about the source document, commonly addressing relationships among numerical conditions, applicable configurations, and restrictions. |
| source_document | string | Web text containing scaffolding design guidance, load classifications, or configuration restrictions used as the basis for answering. |
| reference_answer | string | An accurate answer to the evaluation question based on the source document. |
| supporting_evidence | string | A quotation from the source document or a relevant passage reference supporting the answer. |
| constraint_relationship_summary | string | A summary of how relevant numerical conditions, applicable configurations, and restrictions relate, including their scope or cases where they do not apply. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

