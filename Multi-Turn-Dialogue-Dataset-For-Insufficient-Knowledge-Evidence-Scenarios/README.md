---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Turn Dialogue Dataset for Insufficient Knowledge Evidence Scenarios
---

# Multi-Turn Dialogue Dataset for Insufficient Knowledge Evidence Scenarios

Covers conversations in which knowledge-base evidence is missing, does not support a user's conclusion, or supports only a partial answer. Records pair multi-turn dialogue text with related evidence and show how an assistant can state limitations, avoid unsupported claims, and continue through clarification or a clearly scoped response. The dataset supports reliable response training and evaluation for RAG knowledge-base QA and dialogue supervised fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_dialogue | string | The original multi-turn dialogue, including speaker labels and assistant responses. |
| source_evidence | string | The knowledge-base evidence associated with the dialogue; the value may be empty when no evidence is available. |
| conversation_turns | array | The dialogue parsed into an ordered sequence of speaker turns. |
| evidence_assessment | object | A structured assessment of what the supplied evidence supports and does not support. |
| assistant_strategies | array | Reliable response behaviors demonstrated by the assistant. |
| clarification_needed | boolean | Indicates whether a follow-up question is needed to provide a supported or more complete answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

