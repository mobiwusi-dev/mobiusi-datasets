---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Psychotherapy Dialogue Response Faithfulness Evaluation Dataset
---

# Psychotherapy Dialogue Response Faithfulness Evaluation Dataset

This dataset contains psychotherapy session transcripts, model responses to evaluate, and verifiable claims extracted from those responses with annotations indicating whether each claim is supported by the client's statements, contradicts the dialogue, or goes beyond the available evidence. Its dialogue text and claim-level annotations help measure how faithfully model responses are grounded in session content. It is designed for psychotherapy-domain model evaluation, response quality review, and trustworthiness research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claims | array | Verifiable claims extracted from the model response, each with a groundedness label and supporting annotation details. |
| model_response | string | The model response whose claims are assessed against the conversation transcript. |
| conversation_transcript | string | The source psychotherapy dialogue between the client and therapist. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

