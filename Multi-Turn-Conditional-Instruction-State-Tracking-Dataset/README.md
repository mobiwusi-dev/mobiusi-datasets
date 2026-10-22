---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Turn Conditional Instruction State Tracking Dataset
---

# Multi-Turn Conditional Instruction State Tracking Dataset

This dataset contains multi-turn text conversations in which users establish conditional rules and later add to them, revise them, or invalidate them. Each sample records the full conversation and annotations of the effective rules and expected assistant response at each turn, supporting training in persistent instruction tracking and rule-aware response generation. It is suitable for conditional instruction-following training, dialogue generation, and evaluation of multi-turn instruction handling.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| turn_annotations | array | Annotations for assistant response turns that describe the effective rules and expected response at each point in the conversation. |
| conversation_text | string | The complete source conversation, including user instructions, later rule updates or invalidations, and assistant messages. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

