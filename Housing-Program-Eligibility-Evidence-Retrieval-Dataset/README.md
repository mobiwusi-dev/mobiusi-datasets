---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Housing Program Eligibility Evidence Retrieval Dataset
---

# Housing Program Eligibility Evidence Retrieval Dataset

This dataset brings together web-text queries about housing assistance, affordable housing programs, and related public initiatives, alongside excerpts from official program descriptions and policy documents. Each record identifies an eligibility criterion and includes an evidence quote, its stance, an assessment rationale, and a relevance grade from 0 to 3. It supports training and evaluating housing-policy retrieval and reranking systems, as well as eligibility question answering and evidence discovery.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | The original web-text query asking about eligibility for housing assistance or an affordable housing program. |
| source_url | string | The URL of the webpage or official document from which the program text was collected, when available. |
| source_text | string | Text from an official program description, policy, or eligibility document used to assess the query. |
| evidence_quote | string | The relevant excerpt selected from the official program text to support the eligibility assessment. |
| evidence_stance | string | Indicates whether the evidence supports, excludes, or does not determine the eligibility condition raised by the query. |
| relevance_grade | integer | An ordinal relevance label for ranking the official program text against the query; 0 means irrelevant and 3 means highly relevant. |
| assessment_rationale | string | A concise explanation of how the quoted evidence relates to the query and supports or excludes the stated eligibility condition. |
| eligibility_criterion | string | The specific program requirement or eligibility condition addressed by the evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

