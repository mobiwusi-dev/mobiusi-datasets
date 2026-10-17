---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G SA QoS Flow and Policy Reasoning Dataset
---

# 5G SA QoS Flow and Policy Reasoning Dataset

This question-answer dataset presents 5G Standalone scenarios involving QoS flows, PDU session parameters, policy rules, traffic requirements, and related conditions, alongside answers and reasoning explanations. It focuses on how rule constraints relate to expected handling, supporting consistency assessment, policy conflict detection, and reasoned conclusions. Typical uses include reasoning SFT for 5G core networks, policy validation, and network operations support.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | The derived answer to the question, stating the appropriate conclusion or expected handling. |
| question_text | string | The original question asking for analysis or a conclusion based on the scenario conditions. |
| scenario_text | string | The original text describing relevant QoS flows, PDU session parameters, policy rules, traffic requirements, and other conditions. |
| reasoning_text | string | The derived explanation connecting traffic requirements, QoS flow properties, session context, and policy constraints to the answer. |
| policy_consistency | string | The derived assessment of whether the stated conditions are consistent, conflicting, or insufficient to determine an outcome. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

