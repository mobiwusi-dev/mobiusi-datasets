---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Medical Expense Insurance Claims Process Question Answering Dataset
---

# Medical Expense Insurance Claims Process Question Answering Dataset

This dataset presents question-and-answer content about individual medical expense insurance claims, including application steps, submission deadlines, required materials, and reimbursement procedures. Answers are grounded in claim guides and policy documents. Fields cover questions, reference materials, answers, claim topics, and supporting process details, making the dataset suitable for building retrieval-augmented systems, evaluating open-book question answering, and checking evidence traceability.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer to the claim question, grounded in the provided source material. |
| claim_topic | string | The main process topic addressed by the question, such as application steps, submission deadlines, required materials, or reimbursement. |
| claim_question | string | The original question about claim application steps, submission deadlines, required materials, or reimbursement procedures. |
| source_material | string | The claim guide or policy text provided as the reference input for answering the question. |
| evidence_excerpt | string | A relevant excerpt or paraphrased passage from the source material that supports the answer. |
| required_materials | string | A readable summary of the documents or other materials required for the claim, based on the source material. |
| submission_deadline | string | The applicable deadline for submitting the claim, when specified in the source material; otherwise, indicate that it is not specified. |
| reimbursement_process | string | A readable summary of the steps and conditions for obtaining reimbursement, based on the source material. |
| source_document_title | string | The title of the guide or policy document supporting the answer, when identifiable from the provided source material. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

