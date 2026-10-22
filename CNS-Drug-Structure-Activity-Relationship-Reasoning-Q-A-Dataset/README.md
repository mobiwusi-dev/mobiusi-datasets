---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: CNS Drug Structure–Activity Relationship Reasoning Q&A Dataset
---

# CNS Drug Structure–Activity Relationship Reasoning Q&A Dataset

Designed for central nervous system small-molecule drug discovery, this dataset presents text-based structural differences across compound series alongside experimental results for activity, selectivity, solubility, and related properties. Questions cover analogue comparison, identification of supporting evidence and counterexamples for structure–activity relationships, and analysis of tradeoffs among properties, with concise reasoning answers. It supports training and evaluation of logical reasoning and evidence assessment in medicinal chemistry.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | Concise answer to the question, including the comparison or conclusion supported by the source context. |
| source_text | string | Original text containing the medicinal chemistry question and relevant analogue structures, experimental results, and other context. |
| reasoning_text | string | Brief explanation connecting structural differences to observed activity, selectivity, solubility, or other reported properties. |
| counterevidence | string | Summary of relevant observations that qualify or contradict the proposed structure–activity relationship. |
| property_tradeoffs | string | Explanation of tradeoffs among activity, selectivity, solubility, or other properties discussed in the answer. |
| supporting_evidence | string | Summary of experimental observations that support the stated structure–activity relationship. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

