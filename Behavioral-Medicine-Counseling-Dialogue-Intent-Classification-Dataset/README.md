---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Behavioral Medicine Counseling Dialogue Intent Classification Dataset
---

# Behavioral Medicine Counseling Dialogue Intent Classification Dataset

This dataset contains excerpts from behavioral medicine counseling conversations between patients and professionals about health behavior change. Patient expressions are annotated with intents such as help seeking, information seeking, barrier disclosure, ambivalence, and goal setting. Each sample can include the conversation context, the patient's utterance, intent labels, and a rationale, supporting model fine-tuning, dialogue analysis, and evaluation without replacing professional clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| intent_labels | array | One or more intent categories expressed by the patient, such as help seeking, information seeking, barrier disclosure, ambivalence, or goal setting. |
| intent_rationale | string | A concise explanation of the textual evidence supporting the assigned intent label or labels. |
| conversation_text | string | The original dialogue excerpt between the patient and the professional, including relevant conversational context. |
| patient_utterance | string | The patient utterance or excerpt expressing the intent being annotated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

