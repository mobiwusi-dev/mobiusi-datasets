---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Summary Judgment Case File Evidence Citation Retrieval Dataset
---

# Summary Judgment Case File Evidence Citation Retrieval Dataset

Designed for summary judgment proceedings in commercial litigation, this dataset contains retrieval queries about undisputed material facts and arguments for or against summary judgment, paired with relevant case file records. It connects factual assertions to locatable evidence passages in affidavits, deposition excerpts, documentary evidence, and exhibits, supporting evidence retrieval and knowledge-grounding training based on case records. It can be used to develop and evaluate legal document retrieval applications, but does not replace attorney review of admissibility or legal issues.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_context | object | Describes the undisputed material fact assertion or argument for or against summary judgment to be searched. |
| citation_quality | object | Assesses the completeness and quality of links between factual assertions and specific, potentially admissible case file passages. |
| case_file_records | array | Source case records for retrieval, including affidavits, deposition excerpts, documentary evidence, and exhibits. |
| retrieval_summary | object | Summarizes case file records relevant to the query assertions and how they support those assertions. |
| evidence_citations | array | Links factual assertions or arguments in the query to specifically locatable evidence passages in the case file. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

