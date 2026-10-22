---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Abductive QA Dataset for Structure–Activity Relationship Anomalies in Metabolic Disease Drugs
---

# Abductive QA Dataset for Structure–Activity Relationship Anomalies in Metabolic Disease Drugs

Focused on small-molecule drugs for metabolic diseases, this dataset presents structural differences between analogues, activity or selectivity readouts, and relevant experimental conditions alongside results that deviate from expected structure–activity relationships. The questions ask models to assess possible causes, such as changes in binding mode, conformational effects, or assay conditions, while distinguishing well-supported explanations from weaker hypotheses. It supports abductive reasoning training, structure–activity analysis, and model evaluation in medicinal chemistry.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | A clear, concise answer to the original question that distinguishes well-supported conclusions from weaker possibilities. |
| question_text | string | The user-facing question to be answered, extracted from the source record. |
| raw_qa_record | string | The original question-and-answer text, including compound comparisons, activity or selectivity observations, experimental context, and any supplied reference answer. |
| anomaly_statement | string | A concise description of the observed result that is unexpected or inconsistent with the expected structure–activity relationship. |
| expected_sar_summary | string | The expected structure–activity or selectivity trend implied by the structural changes and available context. |
| candidate_explanations | array | Plausible explanations for the anomalous result, with supporting and contradicting evidence and an explicit evidence-strength assessment. |
| most_likely_explanation | string | The explanation best supported by the available evidence, with a brief justification and appropriate qualification of uncertainty. |
| assay_conditions_summary | string | A summary of experimental conditions relevant to interpreting the reported measurements, such as assay format, target construct, substrate, or incubation conditions. |
| compound_comparison_summary | string | A concise summary of the compared small-molecule analogues and their relevant structural differences. |
| activity_selectivity_readout_summary | string | A summary of the reported activity or selectivity values, including units and comparator relationships when available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

