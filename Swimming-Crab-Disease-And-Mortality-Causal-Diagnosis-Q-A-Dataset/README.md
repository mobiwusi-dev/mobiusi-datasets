---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Swimming Crab Disease and Mortality Causal Diagnosis Q&A Dataset
---

# Swimming Crab Disease and Mortality Causal Diagnosis Q&A Dataset

This dataset focuses on disease and mortality cases in swimming crab aquaculture, covering text-based evidence such as symptoms, farming and management history, water quality conditions, and test results. Its question-and-answer records address plausible causes and causal chains, competing explanations, evidence that could distinguish among causes, and limitations arising from missing information or uncertainty. It supports aquaculture disease reasoning, diagnostic analysis, and causal reasoning evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| symptoms | string | Source text describing observed symptoms, affected animals, timing, severity, and distribution. |
| causal_chain | string | An explanation of the plausible sequence linking initiating factors, intermediate processes, and observed disease or mortality outcomes. |
| test_results | string | Source text describing laboratory, pathogen, or other diagnostic test results, including relevant sampling context when available. |
| causal_caveat | string | Notes on limitations, missing information, and observations that may be associated with the event without being established causes. |
| causal_diagnosis | string | A reasoned assessment of the most plausible cause or causes, with uncertainty stated and conclusions grounded in the source evidence. |
| management_history | string | Source text describing relevant stocking, feeding, handling, treatment, and other farming or management practices. |
| diagnostic_question | string | The original question asking about the disease or mortality event, its possible causes, or evidence needed to assess them. |
| discriminating_evidence | string | Additional observations, measurements, sampling, or tests that could help differentiate the leading causal explanations. |
| alternative_explanations | string | Plausible competing causes or combinations of causes, with a brief explanation of how each fits or conflicts with the evidence. |
| water_quality_information | string | Source text or reported measurements describing water quality conditions and their timing in relation to the case. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

