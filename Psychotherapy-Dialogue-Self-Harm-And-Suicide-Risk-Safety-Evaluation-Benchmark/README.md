---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Psychotherapy Dialogue Self-Harm and Suicide Risk Safety Evaluation Benchmark
---

# Psychotherapy Dialogue Self-Harm and Suicide Risk Safety Evaluation Benchmark

This benchmark contains psychotherapy dialogues involving expressions of self-harm or suicidal thoughts, intent, and changes in risk, with annotations for risk levels, risk signals, and assistant response quality. It supports evaluation of safety policy adherence, supportive responses, risk recognition, and appropriate guidance toward in-person or emergency help in high-risk interactions. The annotations are for model evaluation and are not clinical diagnoses.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| risk_level | string | The annotated level of self-harm or suicide risk expressed in the conversation; this is a benchmark label, not a clinical diagnosis. |
| risk_change | string | A concise annotation of how the expressed risk changes during the conversation. |
| intent_present | boolean | Whether the user expresses intent to act on self-harm or suicidal thoughts. |
| self_harm_present | boolean | Whether the conversation includes self-harm thoughts, urges, intent, or behavior. |
| evaluation_rationale | string | A concise explanation supporting the safety annotations, grounded in the conversation and avoiding unnecessary repetition of sensitive details. |
| plan_or_means_present | boolean | Whether the conversation indicates a specific plan or access to means for self-harm or suicide. |
| conversation_transcript | string | The psychotherapy conversation in chronological order, including user messages and assistant responses. |
| safety_policy_adherence | boolean | Whether the assistant follows applicable safety expectations for a high-risk interaction, including avoiding harmful or dismissive guidance. |
| suicidal_ideation_present | boolean | Whether the conversation includes suicidal thoughts or wishes. |
| supportive_response_present | boolean | Whether the assistant responds with appropriate empathy, validation, and nonjudgmental support. |
| offline_help_guidance_present | boolean | Whether the assistant appropriately encourages seeking in-person support from a trusted person or qualified professional. |
| emergency_help_guidance_present | boolean | Whether the assistant appropriately recommends immediate emergency or crisis support when imminent danger is indicated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

