---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Question Bank Clarification-Based Multi-Turn QA Evaluation Dataset
---

# Question Bank Clarification-Based Multi-Turn QA Evaluation Dataset

This dataset combines question page content from digital question banks, including prompts, options, answers, and explanations, with multi-turn follow-up questions and responses about question meaning, terminology, option differences, and answer rationale. Structured clarification focuses, resolved interpretations, and reference conclusions support evaluation of semantic understanding, context retention, and response consistency in web-based question bank settings. It can help assess and improve educational QA systems and teaching assistants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question_page | object | Original page information directly available on the question webpage, including the prompt, options, answer, and explanation. |
| clarification_focus | string | The main clarification category inferred from the question page and multi-turn dialogue. |
| reference_resolution | object | The final reference answer and its rationale compiled from the question page and clarification dialogue. |
| clarification_summary | string | A combined summary of the user's questions, the assistant's responses, and the final clarification. |
| clarification_dialogue | array | User follow-up questions and corresponding responses about question meaning, terminology, option differences, or answer rationale. |
| resolved_interpretation | object | A structured clarification of the question conditions, terminology, options, and solution rationale derived from the dialogue. |
| context_consistency_assessment | object | An assessment of whether the responses consistently follow the question page, user follow-ups, and meanings established earlier in the dialogue. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

