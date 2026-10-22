---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Knowledge Base QA Context Tracking and Follow-Up Dataset
---

# Knowledge Base QA Context Tracking and Follow-Up Dataset

This dataset contains follow-up questions that rely on earlier entities, references, omitted information, or previous answers, together with the corresponding assistant responses. Its dialogue text and structured turn and follow-up analysis fields represent context carryover and interpretation in multi-turn knowledge base QA. Use it to train or evaluate contextual resolution, conversation state tracking, and coherent response generation for RAG systems, conversational search, and virtual assistants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| turns | array | The conversation parsed into ordered speaker turns. |
| follow_up_analysis | object | The context-dependent follow-up, its resolved meaning, the supporting conversational dependency, and the assistant response. |
| source_conversation | string | The original multi-turn conversation text used as the input source. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

