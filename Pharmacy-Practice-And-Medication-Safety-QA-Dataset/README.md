---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pharmacy Practice and Medication Safety QA Dataset
---

# Pharmacy Practice and Medication Safety QA Dataset

This dataset contains questions, answers, and explanations sourced from pharmacist certification and pharmacy practice resources. It covers prescription review, drug interactions, adverse reactions, dosage principles, and medication storage, with structured prompts and target responses for supervised fine-tuning. It can support training and evaluation of pharmacy knowledge question answering and medication safety understanding.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_qa | object | Original questions and explanations collected from pharmacist certification or pharmacy practice resources. |
| sft_prompt | string | A model input prompt composed from the source question and answer options for supervised fine-tuning. |
| sft_response | string | A normalized pharmacy QA response based on the standard answer and its explanation. |
| knowledge_topics | array | Pharmacy topics inferred from the question and explanation, such as prescription review, drug interactions, adverse reactions, dosage principles, or medication storage. |
| safety_risk_points | array | Potential medication risks, contraindications, monitoring requirements, or safety precautions identified in the QA content. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

