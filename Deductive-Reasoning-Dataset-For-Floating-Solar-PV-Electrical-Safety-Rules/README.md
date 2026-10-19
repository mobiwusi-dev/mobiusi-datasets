---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Deductive Reasoning Dataset for Floating Solar PV Electrical Safety Rules
---

# Deductive Reasoning Dataset for Floating Solar PV Electrical Safety Rules

This dataset provides question-answer examples about electrical configurations, equipment states, isolation and protection rules, and cable routing conditions in floating solar PV arrays. Each example includes facts, applicable rules, a question, a verdict, and a reasoning chain; models must rely only on the information provided and identify cases where the evidence is insufficient. It supports reasoning fine-tuning, logical capability evaluation, and safety-rule question answering for floating solar PV applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | The conclusion derived from the supplied facts and rules; marked as indeterminate when the information does not support a valid or invalid verdict. |
| question | string | The operation or conclusion that must be evaluated using the supplied facts and rules. |
| safety_rules | string | Applicable rules provided in the prompt for electrical isolation, protection, and cable routing. |
| reasoning_chain | string | The logical steps connecting relevant facts and applicable rules to the verdict. |
| electrical_facts | string | Electrical configurations, equipment states, and related facts about the floating solar PV array provided in the prompt. |
| supporting_premises | string | The prompt facts and rules actually used in the reasoning, without introducing information from outside the prompt. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

