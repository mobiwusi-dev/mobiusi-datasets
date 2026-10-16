---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Medical Instruction Comprehension Dataset for Learners
---

# Korean Medical Instruction Comprehension Dataset for Learners

This dataset contains Korean hospital intake instructions, appointment notices, medication guidance, examination preparation sheets, and health management announcements, organized as JSON supervision with document categories, process steps, time requirements, precautions, and contraindications. It highlights key requirements and risk-related information in everyday medical documents, supporting training and evaluation of Korean semantic understanding, information extraction, and learner-oriented explanations. It is suited to Korean learning assistance, medical document comprehension, and research on high-stakes text processing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| process_steps | array | Steps extracted from the source and arranged in execution order for care visits, appointments, medication, or examinations. |
| document_purpose | string | A summary of the main action the document asks readers to take or the key information it aims to convey. |
| key_korean_terms | array | Medical, appointment, time-related, and precaution-related Korean terms extracted from the source, with explanations. |
| precaution_items | array | Operational precautions, risk warnings, and information that should be proactively shared with medical staff, extracted from the source. |
| risk_alert_level | string | An alert level assessed from contraindications, medication guidance, examination preparation, emergency symptoms, and related content. |
| contraindications | array | Prohibited actions, eligibility limits, restrictions for specific populations, and exceptions extracted from the source. |
| document_category | string | The medical instruction document category identified from the source text. |
| time_requirements | array | Appointment, arrival, medication, fasting, examination, or follow-up time constraints extracted from the medical instructions. |
| learner_explanation | object | A plain-language Chinese explanation for Korean learners, including language-learning notes and high-risk warnings. |
| symptom_descriptions | array | Symptoms, affected areas, severity, and onset time mentioned in the source, organized as information that is easy for learners to understand. |
| understanding_points | array | Key question-and-answer items for supervised learning, including questions, reference answers, and supporting source text. |
| examination_preparation | object | Fasting, hydration, medication adjustments, items to bring, and arrival requirements extracted from examination preparation documents. |
| medication_instructions | object | Medication names, doses, frequency, treatment duration, and missed-dose guidance extracted from medication instructions; may be an empty string for documents unrelated to medication. |
| raw_korean_medical_text | string | Original Korean text from hospital intake instructions, appointment notices, medication guidance, examination preparation sheets, or health management announcements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

