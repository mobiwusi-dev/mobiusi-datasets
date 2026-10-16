---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Digital Textbook Knowledge Boundaries and Applicability Conditions QA Dataset
---

# Digital Textbook Knowledge Boundaries and Applicability Conditions QA Dataset

This dataset contains professional question-answer pairs derived from web-based textbook material, including qualified definitions, theorem conditions, rule exceptions, scopes of applicability, and comparisons. Answers are designed to state the prerequisites and boundaries under which a conclusion holds. Each record includes the source text, question type, knowledge conclusion, applicability conditions, boundaries and exceptions, a complete answer, and an evidence excerpt, supporting domain-specific supervised fine-tuning that helps reduce overgeneralization.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A user-facing answer that explains the knowledge conclusion, its conditions and scope, and any relevant exceptions or cases where it does not apply. |
| question | string | A domain-specific question derived from the source text that prompts the respondent to explain the conclusion's conditions, scope, or exceptions. |
| source_text | string | Web-based textbook content or a relevant passage used to generate the question and answer, typically containing a definition, theorem, rule, scope, limitation, or comparison. |
| question_type | string | The category of textbook knowledge addressed by the question. |
| evidence_quote | string | A key quotation from the textbook that supports the question, conclusion, and boundary analysis, enabling verification that the answer reflects the source. |
| knowledge_conclusion | string | An accurate summary of the core knowledge point that does not generalize beyond the conditions stated in the source. |
| boundary_and_exceptions | array | Source-stated cases where the conclusion does not apply, rule exceptions, limitations on comparisons, or other boundaries that can prevent incorrect generalization. |
| applicability_conditions | array | The prerequisites, scope, definition conventions, or variable constraints that must hold for the conclusion to apply. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

