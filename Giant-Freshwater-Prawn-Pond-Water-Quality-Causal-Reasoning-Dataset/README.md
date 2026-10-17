---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Giant Freshwater Prawn Pond Water Quality Causal Reasoning Dataset
---

# Giant Freshwater Prawn Pond Water Quality Causal Reasoning Dataset

Focused on giant freshwater prawn pond aquaculture, this question-answer dataset covers dissolved oxygen, ammonia nitrogen, pH, temperature, feeding, and aeration management. Samples ask models to analyze how farming conditions affect water quality and prawn condition, distinguishing likely direct causes, contributing factors, and accompanying observations. It supports causal reasoning supervised fine-tuning, as well as training and evaluation of context-based explanations and management judgments.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| likely_causes | string | Lists and explains the factors most likely to cause the reported water quality or prawn condition changes, distinguishing direct causes from contributing factors. |
| question_context | string | The original input, including pond dissolved oxygen, ammonia nitrogen, pH, temperature, feeding, aeration management, and the question to answer. |
| uncertainty_notes | string | Identifies missing information, alternative explanations, and indicators that may require further monitoring or verification. |
| causal_explanation | string | Explains how aquaculture conditions cause or affect water quality changes and giant freshwater prawn condition, describing the main causal relationships. |
| management_judgment | string | Uses the causal analysis to provide judgments and recommendations for feeding, aeration, or other aquaculture management measures. |
| accompanying_observations | string | Describes water quality indicators, prawn behavior or condition, and farming observations that occur alongside the issue but cannot be assumed to cause it directly. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

