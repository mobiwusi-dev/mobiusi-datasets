---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Educational Question Evidence Retrieval Dataset
---

# Educational Question Evidence Retrieval Dataset

This dataset connects questions from educational question banks and their standard answers with webpage text, candidate passages, and precise supporting evidence spans. Each structured record can include the question and answer, a source webpage, retrieved passages, and the relationship between evidence spans and the standard answer, supporting the development and evaluation of evidence retrieval and answer attribution in education. It helps models locate relevant information in web content and makes the grounding of educational answers more traceable.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| webpage_input | object | The original webpage record used as a source for locating evidence that supports the answer. |
| evidence_spans | array | Precise text spans within retrieved passages, including their relationship to the standard answer. |
| retrieved_passages | array | Passages selected from the source webpage as potentially relevant to the question and answer. |
| question_answer_input | object | The original question and its standard answer, provided as the input for evidence retrieval. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

