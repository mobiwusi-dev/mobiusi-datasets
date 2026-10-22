---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: French Learner Error Analysis and Evidence-Based Q&A Dataset
---

# French Learner Error Analysis and Evidence-Based Q&A Dataset

This dataset provides structured question-answer examples about representative errors made by French learners, addressing why an expression is incorrect, which grammar or usage rule applies, and how to express the intended meaning correctly. Records can include the erroneous expression, learner question, error analysis, corrected expression, applicable rule, and supporting reference details such as title, excerpt, and locator. It is designed for supervised fine-tuning and evaluation of French learning assistants, grammar correction systems, and domain-specific question-answering models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | A clear response addressing the learner's question and explaining the error and its correction. |
| applicable_rule | string | The specific grammar or usage rule that explains the error and supports the correction. |
| learner_question | string | The question asking why the expression is incorrect, which rule applies, or how to express the intended meaning correctly. |
| error_explanation | string | An explanation of why the erroneous expression is incorrect or inappropriate in context. |
| reference_excerpt | string | The relevant excerpt or a concise, faithful summary of the supporting grammar or usage material. |
| reference_locator | string | A source locator for the supporting material, such as a URL, page number, section, or dictionary entry. |
| corrected_expression | string | A grammatically or idiomatically appropriate French expression that preserves the intended meaning. |
| erroneous_expression | string | The French expression containing the representative learner error, as provided in the source item. |
| reference_material_type | string | Whether the supporting material is primarily a grammar reference or a usage reference. |
| reference_material_title | string | The title of the grammar or usage material supporting the answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

