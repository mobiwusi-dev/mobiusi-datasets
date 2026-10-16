---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Reading and Writing Passage Evidence Retrieval Dataset
---

# SAT Reading and Writing Passage Evidence Retrieval Dataset

Organized as JSON records, the dataset covers SAT Reading and Writing questions, short passages, candidate evidence snippets, correct answers, and evidence-span annotations. It also includes retrieval queries, evidence selection results, and summaries linking answers to their supporting text. The collection supports building and evaluating systems that retrieve passage evidence for specific questions, including SAT tutoring QA and retrieval-augmented generation workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_record | object | The original question, passage, candidate evidence, and annotation information from a dataset JSON record. |
| retrieval_query | string | A query text generated from the SAT prompt, passage, and answer information to retrieve supporting evidence. |
| grounding_summary | object | A summary of the relationship between the correct answer and its supporting passage evidence. |
| evidence_selection | array | Results of assessing candidate evidence snippets for relevance and determining whether they support the answer. |
| gold_evidence_text | string | The complete supporting text extracted from the short passage according to the evidence-span annotation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

