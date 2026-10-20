---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Biobank Cohort Representativeness Evidence Reasoning Dataset
---

# Biobank Cohort Representativeness Evidence Reasoning Dataset

This dataset draws on academic papers about biobank cohort recruitment, participant composition, and selection bias to create scientific reasoning questions with exemplar answers that require synthesis across studies. It focuses on assessing how representative a cohort is of its target population and how recruitment methods and population differences may affect the external validity and scope of research findings. The data supports evidence synthesis, cohort assessment, and careful reasoning model training in biobank research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | A concise, coherent, evidence-based response to the reasoning question that assesses representativeness and explains its implications for the scope of research findings. |
| source_materials | string | Excerpts from one or more academic papers, study context, and citation details used to answer the question. Retain information relevant to recruitment methods, participant composition, and selection bias. |
| evidence_synthesis | string | Summarizes and compares relevant study evidence, explaining how each piece supports or limits judgments about cohort representativeness. |
| reasoning_question | string | A question that asks the model to synthesize paper evidence, assess cohort representativeness, and analyze implications for the scope of research findings. |
| scope_implications | string | Explains how cohort representativeness and selection bias affect generalizability, external validity, and the population to which findings may apply, without extrapolating beyond the evidence. |
| selection_bias_analysis | string | Analyzes potential participant self-selection, recruitment channel constraints, and population differences, as well as the biases they may introduce. |
| uncertainty_and_caveats | string | Identifies evidence gaps, differences between studies, and other limitations that may affect the assessment, distinguishing established facts from inference. |
| representativeness_assessment | object | An evidence-based judgment of how representative the cohort is of its target population, with supporting rationale. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

