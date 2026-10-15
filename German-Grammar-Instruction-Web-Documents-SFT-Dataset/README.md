---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: German Grammar Instruction Web Documents SFT Dataset
---

# German Grammar Instruction Web Documents SFT Dataset

This dataset covers German grammar instruction from web pages, including rule explanations, example sentences, exceptions, and exercise prompts. It organizes the source HTML alongside document overviews, structured grammar sections, and rule records, with supervision for semantic explanations, rule applicability judgments, and cross-paragraph question answering. It supports training models to interpret grammar concepts in context and developing German learning assistants and document question-answering systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_html | string | The original HTML content of a German grammar teaching page, provided as the raw input for data processing. |
| grammar_rules | array | German grammar rules extracted from the instructional document, including applicability conditions, exceptions, example sentences, and exercise prompts. |
| grammar_sections | array | Instructional sections segmented and structured in the original page order, preserving their content and teaching function. |
| document_overview | object | An overview extracted from the source page, including its title, grammar topic, learner level, document language, and overall summary. |
| cross_paragraph_qa | array | Questions requiring information from multiple instructional sections, paired with answers, supporting section references, and reasoning. |
| semantic_explanations | array | Chinese-language semantic explanations of rules, examples, or key expressions, including interpretations grounded in context. |
| rule_applicability_judgments | array | Judgments on whether a rule applies to a specific German sentence or context, with supporting rationale and confidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

