---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: University Entrance Exam Syllabus and Tested-Content Question Answering Dataset
---

# University Entrance Exam Syllabus and Tested-Content Question Answering Dataset

This dataset combines web text from university entrance exam syllabi and subject guides, including knowledge scopes, question formats, and competency requirements, with evidence-based question-answer records. It captures exam and subject context, knowledge scope, question intent, evidence alignment, and assessment boundaries to help models find answer sources and verify their relevance. It supports training and evaluation for exam information QA, study assistance, educational search, and document question answering.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_basis | string | Explains how the reference answer follows from the exam syllabus, subject guide, or question format rules, and identifies the applicable assessment boundaries. |
| exam_context | object | Exam, subject, and syllabus section information inferred from the webpage text and question-answer content. |
| raw_qa_record | object | The original candidate question, reference answer, evidence text, and source information. |
| knowledge_scope | array | A list of knowledge points, topic scopes, or tested content extracted from syllabus evidence. |
| question_intent | string | The primary intent of the candidate's question, such as asking about exam scope, question format rules, competency requirements, or preparation boundaries. |
| evidence_alignment | object | The relationship between the answer and supporting syllabus evidence, for retrieval and verification. |
| source_webpage_text | string | Original text collected from exam syllabus or subject guide webpages, preserving the source wording for retrieval. |
| boundary_constraints | array | Explicit tested scopes, limitations, excluded content, or prerequisites extracted from the evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

