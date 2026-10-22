---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Context-Dependent IT Support Intent Classification Dataset
---

# Context-Dependent IT Support Intent Classification Dataset

This dataset contains multi-turn chat conversations from endpoint and digital workspace support scenarios, with the primary IT support intent labeled for a designated turn along with its context dependency. It covers standalone requests, follow-ups, clarified intent, and intent changes, supporting models that interpret requests in light of conversation history. Typical uses include fine-tuning IT support chatbots, evaluating intent recognition, and researching support request routing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| intent_label | string | The primary IT support intent expressed in the target turn, interpreted using conversation context when necessary. |
| intent_changed | boolean | Indicates whether the target turn reflects a change from the user's preceding intent. |
| target_turn_index | integer | The zero-based index of the turn whose intent is being classified. |
| previous_intent_label | string | The user's intent immediately before the target turn, or null when no previous intent is available or applicable. |
| context_dependency_type | string | The target turn's relationship to the preceding conversation: standalone request, follow-up request, clarification, or intent change. |
| conversation_transcript | string | The complete multi-turn endpoint or digital workspace support conversation, with speaker turns in chronological order. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

