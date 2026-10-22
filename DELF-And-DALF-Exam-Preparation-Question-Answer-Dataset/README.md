---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: DELF and DALF Exam Preparation Question-Answer Dataset
---

# DELF and DALF Exam Preparation Question-Answer Dataset

This dataset organizes questions and answers about DELF and DALF exam levels, question formats, task requirements, and scoring criteria, using specified exam guides and preparation materials. Records include the reference material, answer, relevant exam details, supporting evidence, and source location. It supports French exam knowledge QA and domain-specific supervised fine-tuning for answering questions from a defined source set.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A clear answer supported by the supplied reference material, without relying on unprovided external information. |
| question | string | The exam-related question to answer using only the supplied reference material. |
| exam_level | string | The DELF or DALF level relevant to the question, as stated or supported by the reference material. |
| question_type | string | The examination component or question format relevant to the question, as identified in the reference material. |
| source_locator | string | The available location of the supporting evidence, such as a section heading, page number, or paragraph identifier. |
| scoring_criteria | string | The scoring standards or assessment criteria relevant to the question, as described in the reference material. |
| task_requirements | string | The task instructions, expected actions, or response requirements relevant to the question. |
| reference_material | string | The supplied examination guide or preparation material used as the closed source for answering the question. |
| supporting_evidence | string | A relevant quotation or faithful excerpt from the reference material that supports the answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

