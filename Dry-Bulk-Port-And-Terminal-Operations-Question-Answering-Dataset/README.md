---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Dry Bulk Port and Terminal Operations Question Answering Dataset
---

# Dry Bulk Port and Terminal Operations Question Answering Dataset

This dataset covers dry bulk cargo handling, terminal service procedures, and operating guidelines. It pairs source webpage text with questions, answers, and evidence passages, with each answer grounded in the supplied source text. It is suitable for training and evaluating retrieval-augmented generation systems, retrieving port operations knowledge, and developing document question answering applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer based on the source webpage text that stays within the scope supported by the evidence. |
| question | string | A question about port or terminal operations information contained in the source webpage text. |
| evidence_passages | string | Excerpts from the source webpage that support the answer. Multiple passages are separated by line breaks. |
| source_webpage_text | string | Webpage text on dry bulk cargo handling, terminal service procedures, or operating guidelines that serves as the basis for the question and answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

