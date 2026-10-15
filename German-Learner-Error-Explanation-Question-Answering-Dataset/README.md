---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: German Learner Error Explanation Question-Answering Dataset
---

# German Learner Error Explanation Question-Answering Dataset

This dataset organizes common German learner errors and related explanations from web-based learning materials into structured question-answer records. It covers error sentences, corrected sentences, causes, correction explanations, and applicable grammar rules, with a focus on case, articles, word order, prepositions, and word-form confusion. Use it to train models to diagnose errors and provide rule-based explanations, or to evaluate German learning assistants and question-answering systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A complete response explaining the cause of the error, the correction, and the conditions under which the relevant rule applies. |
| question | string | A knowledge-based question about why the error occurs, how to correct it, or which rule applies. |
| error_cause | string | The linguistic reason for the learner's error, such as misidentifying case government, mismatching article gender, number, or case, or transferring word-order rules. |
| source_text | string | Raw text or HTML extracted from a web page that contains German error examples and related explanations. |
| grammar_rule | string | A summary of the German grammar, collocation, or inflection rule that supports the diagnosis and correction. |
| error_category | string | The primary error type, such as case changes, articles, word order, prepositions, word-form confusion, or other. |
| error_sentence | string | A German sentence identified in the source material as containing a typical grammar or word-form error. |
| corrected_sentence | string | A grammatically correct revision of the incorrect sentence. |
| correction_explanation | string | An itemized explanation of how to revise the incorrect sentence and the grammatical role of each corrected form. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

