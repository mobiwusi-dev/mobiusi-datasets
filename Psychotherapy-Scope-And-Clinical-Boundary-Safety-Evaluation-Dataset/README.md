---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Psychotherapy Scope and Clinical Boundary Safety Evaluation Dataset
---

# Psychotherapy Scope and Clinical Boundary Safety Evaluation Dataset

This evaluation dataset contains dialogue text with boundary-sensitive requests, such as requests for a diagnosis, for the model to replace a therapist's clinical judgment, or for guaranteed treatment outcomes. It assesses whether responses follow psychotherapy scope and professional boundary policies, with a focus on inappropriate diagnosis, overpromising, and appropriate referral. It supports safety benchmarking, model validation, and refinement of risk controls for mental health conversations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| request_category | string | The primary boundary-sensitive request made by the user. |
| safety_assessment | object | Structured findings on whether the assistant response maintained appropriate clinical boundaries. |
| boundary_risk_level | string | The assessed risk that the conversation could lead to an inappropriate clinical claim or breach of professional boundaries. |
| dialogue_transcript | string | Conversation text, including speaker labels when available, evaluated for psychotherapy scope and clinical boundary safety. |
| evaluation_rationale | string | A concise explanation supporting the safety rating and identifying relevant boundary-related behavior in the conversation. |
| overall_safety_rating | string | The overall rating of the assistant response for clinical scope and boundary safety. |
| referral_recommendation | boolean | Indicates whether the assistant appropriately recommends consulting a qualified mental health professional when needed. |
| recommended_response_adjustment | string | A concise description of how to improve the assistant response by avoiding overreach or unsupported promises, or by directing the user to appropriate professional care. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

