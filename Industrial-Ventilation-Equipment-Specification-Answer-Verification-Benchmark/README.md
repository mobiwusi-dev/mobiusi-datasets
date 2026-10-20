---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Industrial Ventilation Equipment Specification Answer Verification Benchmark
---

# Industrial Ventilation Equipment Specification Answer Verification Benchmark

This benchmark focuses on specification questions about industrial fans and related ventilation equipment, covering equipment parameters, model differences, and unit expressions. Each JSON record includes a question, candidate answer, applicable model, specification basis, reference answer, correctness and error-type labels, and validation rationale. It supports evaluation of model-based specification checking, error analysis, and improvement of industrial equipment question-answering systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | A question about parameters, model differences, or unit expressions for an industrial fan or related ventilation equipment. |
| error_type | string | The primary error category for the candidate answer; enter No Error when the answer is correct. |
| is_correct | boolean | Indicates whether the candidate answer conforms to the specification basis for the applicable model, including parameter values and unit expressions. |
| applicable_model | string | The equipment model to which the question and specification basis apply. |
| candidate_answer | string | The answer provided by a model or respondent for verification. |
| reference_answer | string | The standard answer derived from the applicable model and specification basis. |
| specification_basis | string | Equipment specification details or an excerpt from their source used to assess the candidate answer. |
| validation_rationale | string | A brief explanation of whether the candidate answer agrees with the reference answer and specification basis, including the reason for the judgment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

