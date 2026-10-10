---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Catfish Pond Hypoxia Event Causal Reasoning Dataset
---

# Catfish Pond Hypoxia Event Causal Reasoning Dataset

This dataset presents question-and-answer examples about low dissolved oxygen in catfish ponds and related events such as surface gasping, stress, or mortality. The examples cover event timing, weather, water quality, algal conditions, feeding, aeration, and fish behavior, and ask models to analyze plausible causal chains, distinguish direct triggers from contributing factors, and identify evidentiary gaps and uncertainty. It supports causal diagnosis, aquaculture incident analysis, and reasoning-focused supervised fine-tuning (SFT).

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A complete natural-language response covering the plausible causal chain, assessment of the direct trigger, distinction between related factors, and evidence gaps. |
| causal_chain | array | A sequence of possible links that may lead to low dissolved oxygen and abnormal fish behavior, with hypotheses clearly distinguished from established facts. |
| event_context | object | Raw observations describing the event timing, weather, water quality, algal conditions, feeding, aeration, and fish behavior. |
| evidence_gaps | array | Missing measurements, timing information, or other uncertainties that prevent the available record from supporting a definitive causal conclusion. |
| direct_trigger | string | The factor most likely to have directly triggered surface gasping, stress, or mortality; explicitly states when the evidence is insufficient to determine one. |
| related_factors | array | Factors that may be associated with the event or increase its risk, distinguished from the direct trigger. |
| diagnosis_summary | string | A concise synthesis of the main assessment, the strength of the proposed causal relationships, and the limits of the conclusion. |
| diagnostic_question | string | A question about the cause of hypoxia, causal relationships, or whether the available evidence is sufficient to diagnose a pond event. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

