---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Collision Insurance Coverage Terms Evidence Retrieval Dataset
---

# Collision Insurance Coverage Terms Evidence Retrieval Dataset

This dataset organizes web-based collision insurance policy text and related explanations covering coverage scope, deductibles, exclusions, and claim conditions, alongside claim questions, clause summaries, and supporting evidence passages. Source URLs are retained, and the records cover key steps from locating policy terms to retrieving evidence for claim assessments. The dataset does not establish a universal standard for claim decisions; actual assessments should follow the applicable policy and relevant regulations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_url | string | URL of the webpage from which the policy content was collected. |
| claim_question | string | Claim-related question to be answered using the policy terms and supporting evidence. |
| policy_webpage | string | Raw webpage text containing collision insurance policy terms and related explanations. |
| claim_assessment | string | Answer or reasoned assessment of the claim question based on the extracted policy terms. |
| deductible_summary | string | Summary of the applicable collision coverage deductible, including conditions or variations stated in the source. |
| exclusions_summary | string | Summary of exclusions relevant to the claim question, based on the source policy content. |
| retrieved_evidence | array | Source passages that support or qualify the claim assessment, including relevance and source locations. |
| policy_clause_records | array | Relevant clauses extracted from the source webpage and categorized by their role in collision coverage or claim handling. |
| claim_conditions_summary | string | Summary of relevant notice, documentation, eligibility, or other claim conditions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

