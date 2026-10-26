---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Luxury Hotel Multi-Turn Contextual Intent Classification Dataset
---

# Luxury Hotel Multi-Turn Contextual Intent Classification Dataset

This dataset contains multi-turn chat excerpts between hotel guests and staff, with intent labels for the guest messages being classified. It focuses on follow-up messages, references, and elliptical expressions that require prior turns for interpretation, helping models identify guest needs from full conversational context rather than isolated sentences. It supports intent classification fine-tuning, dialogue understanding evaluation, and service workflow improvement for luxury hotel chat operations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| turn_count | integer | The number of messages in the conversation transcript. |
| intent_label | string | The annotated intent category for the guest message being classified. |
| current_guest_message | string | The guest message whose intent is being classified, extracted from the conversation transcript. |
| conversation_transcript | string | The complete multi-turn chat excerpt, with speaker labels and messages in chronological order. |
| prior_conversation_context | string | The messages preceding the current guest message, retained to support context-dependent interpretation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

