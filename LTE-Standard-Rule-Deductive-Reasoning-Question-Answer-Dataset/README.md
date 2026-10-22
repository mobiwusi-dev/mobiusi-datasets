---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: LTE Standard-Rule Deductive Reasoning Question-Answer Dataset
---

# LTE Standard-Rule Deductive Reasoning Question-Answer Dataset

This dataset presents LTE protocol rules, conditions, facts, and conclusions to evaluate in question-answer examples. Each example includes step-by-step reasoning and a label indicating whether the conclusion is supported, with answers derived only from the information provided in the prompt. It is suited to LTE technical QA, rule-based reasoning training, and conclusion-support evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_case | string | The LTE protocol rules, conditions, facts, question, and proposed conclusion provided for evaluation. |
| reasoning_steps | string | A step-by-step derivation using only the rules and facts stated in the source case. |
| answer_supported | boolean | Indicates whether the proposed conclusion follows from the LTE rules and facts provided. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

