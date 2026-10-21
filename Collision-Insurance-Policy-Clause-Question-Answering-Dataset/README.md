---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Collision Insurance Policy Clause Question Answering Dataset
---

# Collision Insurance Policy Clause Question Answering Dataset

This dataset organizes question-and-answer text grounded in collision insurance policy clauses covering insured losses, eligible vehicles and drivers, liability limits, and exclusions. Each record includes the source clause, question, answer, supporting reference, supporting quote, and coverage topic, linking each response to its policy basis. It supports insurance policy understanding, customer inquiry assistance, and training or evaluation of retrieval-augmented generation systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer derived from the policy clause and responsive to the question. |
| question | string | The original question about collision coverage, eligible vehicles or drivers, liability limits, or exclusions. |
| coverage_topic | string | The main collision coverage topic addressed by the question, such as covered loss, eligible vehicle, driver, limit, or exclusion. |
| supporting_quote | string | The exact or closely transcribed policy wording that supports the answer. |
| policy_clause_text | string | The original collision coverage policy clause used as the source for answering the question. |
| supporting_clause_reference | string | The section number, heading, or other reference identifying where the answer is supported in the policy. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

