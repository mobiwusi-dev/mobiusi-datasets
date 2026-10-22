---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G SA Protocol Flow Deductive Reasoning QA Dataset
---

# 5G SA Protocol Flow Deductive Reasoning QA Dataset

This dataset focuses on representative 5G SA procedures, including registration and PDU session establishment, and presents protocol messages, states, and explicit rules as premises. Models use these facts to infer reachable states, identify permitted procedure branches, or assess whether a conclusion is supported, with a rationale for each answer. It is suited to protocol understanding, procedure-state reasoning, and reasoning-oriented supervised fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The conclusion derived from the protocol facts, such as a reachable state, a permitted branch, or whether a claim is supported. |
| question | string | A question asking for a reachable state, an allowed procedure branch, or an assessment of a protocol conclusion based on the provided facts. |
| reasoning | string | A concise derivation linking the provided protocol facts and explicit rules to the answer. |
| protocol_facts | string | Messages, protocol states, and explicit rules provided as premises for deduction. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

