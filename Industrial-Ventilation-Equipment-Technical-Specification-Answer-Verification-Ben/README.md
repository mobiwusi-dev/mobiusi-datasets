---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Industrial Ventilation Equipment Technical Specification Answer Verification Benchmark
---

# Industrial Ventilation Equipment Technical Specification Answer Verification Benchmark

This benchmark uses product webpages and technical specification text for industrial fans, ventilation units, and related equipment as evidence for questions about key attributes such as airflow, static pressure, power, and dimensions. Each record includes a candidate answer, a verification label indicating whether it is supported, contradicted, or not established by the source, and an explanation with relevant evidence. It supports evaluation of models that verify technical information about industrial ventilation equipment, as well as analysis of answer verification and evidence assessment capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Source passages and their relevance to the verification decision. |
| question | string | Question about a technical specification for industrial ventilation equipment. |
| source_content | string | Product webpage or technical specification text used as the evidence source. |
| candidate_answer | string | Answer to be checked for technical accuracy against the source content. |
| verification_label | string | Classification of whether the candidate answer is supported, contradicted, or not established by the source. |
| specification_attribute | string | Specification category addressed by the question, such as airflow, pressure, power, or dimensions. |
| verification_explanation | string | Concise rationale for the verification decision, including relevant units or qualifications where applicable. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

