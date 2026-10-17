---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Giant Freshwater Prawn Health and Mortality Event Causal Reasoning Dataset
---

# Giant Freshwater Prawn Health and Mortality Event Causal Reasoning Dataset

This question-answer text dataset covers abnormal, disease, and mortality events in giant freshwater prawn aquaculture, with scenarios that include clues about pathogens, water quality stress, husbandry changes, and transmission conditions. Samples guide models to propose candidate causes, trace plausible causal chains, and identify information that is still missing. The data supports training and evaluating careful, explainable causal analysis of giant freshwater prawn health issues.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| causal_chain | array | A sequence of proposed links from potential triggers to health abnormalities or mortality, distinguishing known information from inferred steps. |
| case_question | string | The input scenario describing an abnormal, disease, or mortality event in aquaculture and the question to be answered. |
| candidate_causes | array | Possible causes suggested by the scenario, which may include pathogens, water quality stress, husbandry changes, and transmission conditions. |
| missing_evidence | array | Observations, test results, or records not provided in the scenario that would help assess or distinguish candidate causes. |
| cautious_assessment | string | A conditional assessment based on available information, stating the leading possibilities, uncertainties, and reasons to avoid over-attribution. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

