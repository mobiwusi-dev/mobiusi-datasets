---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Score Components and Score Report Q&A Dataset
---

# SAT Score Components and Score Report Q&A Dataset

This dataset brings together web-based question-and-answer content and related test-preparation inquiries about SAT total and section scores, score interpretation, percentiles, score sending, and score report reading. Its coverage of common scoring rules and reporting procedures supports clear, context-aware answers to SAT score questions. It is suited to domain-specific supervised fine-tuning, response quality evaluation, and educational advising applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| score_facts | object | Facts summarized from the original web Q&A about SAT score ranges, section composition, and scoring rules. |
| web_qa_record | object | The original structured input for a web-based Q&A sample, including the question, reference answer, and source webpage content. |
| question_intent | string | The primary inquiry intent inferred from the user's question. |
| report_guidance | object | Guidance extracted from the Q&A on score interpretation, score sending, and reading SAT score reports. |
| knowledge_topics | array | SAT knowledge topics extracted from the Q&A, such as total scores, section scores, percentiles, score sending, and report fields. |
| response_annotation | object | A structured summary of the reference answer for SAT domain-specific supervised fine-tuning and response quality analysis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

