---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Phase IV Real-World Evidence Bias Reasoning Dataset
---

# Phase IV Real-World Evidence Bias Reasoning Dataset

This dataset presents short scenarios and question-answer tasks based on Phase IV post-marketing real-world studies, covering details such as study design, population, exposure, outcomes, and follow-up. It focuses on how confounding, selection bias, loss to follow-up, and group differences may affect study conclusions, with structured information on bias type, likely impact, evidence-based interpretation, and reasoning boundaries. It supports medical reasoning training, real-world evidence assessment, and evaluation of bias identification.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| bias_type | string | The principal bias mechanism or study limitation identified from the scenario, such as confounding, selection bias, or loss to follow-up. |
| study_scenario | string | The source description of the Phase IV real-world study, including relevant design, population, exposure, outcome, and follow-up details. |
| answer_rationale | string | The logical explanation supporting the response and distinguishing the evidence provided from assumptions that are not justified. |
| reference_answer | string | The answer supplied with the source record, used as the reference for the reasoning task. |
| reasoning_boundary | string | The limits of what can be inferred from the scenario, including missing information or uncertainty that prevents a stronger conclusion. |
| reasoning_question | string | The source question asking how bias, confounding, attrition, or group differences may affect the study conclusion. |
| likely_conclusion_impact | string | An evidence-grounded description of how the identified issue could influence the study conclusion, including direction when the scenario supports it. |
| evidence_based_interpretation | string | A concise interpretation that links the scenario details to the potential effect on the conclusion without asserting unsupported causal claims. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

