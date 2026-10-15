---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Arabic Orthography and Hamza Writing Rules QA Dataset
---

# Arabic Orthography and Hamza Writing Rules QA Dataset

Compiled from Arabic spelling instruction webpages, this dataset covers closed-domain questions on hamza position and seat letters, word joining and separation, final letters, ta marbuta, and spelling exceptions. Records provide normalized questions and answers, with rule categories, statements, analyses, and examples where available, supporting Arabic writing-rule retrieval, domain fine-tuning, and QA evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct answer based on the original webpage content, including the relevant rule decision and explanation. |
| examples | array | Arabic words, letter forms, or spelling examples used to explain the rule, with accompanying explanations. |
| keywords | array | Arabic orthography keywords extracted from the question and answer for retrieval or categorization. |
| question | string | A clear, closed-domain question about Arabic orthography, derived from the original QA content. |
| has_exception | boolean | Indicates whether the QA content involves a spelling exception or special convention. |
| rule_category | string | The main Arabic orthography rule category addressed by the QA record. |
| source_record | object | The original question-and-answer content collected from a spelling instruction webpage, together with source page information. |
| hamza_analysis | object | A structured explanation of hamza position, seat letter, and decision criteria when relevant; may be empty when the question does not concern hamza. |
| rule_statement | string | A concise statement of the core spelling convention, suitable for rule-based decisions. |
| exception_notes | string | Notes on exceptions, special word forms, traditional spellings, or cases where a rule should not be generalized. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

