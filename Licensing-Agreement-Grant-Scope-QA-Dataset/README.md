---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Licensing Agreement Grant Scope QA Dataset
---

# Licensing Agreement Grant Scope QA Dataset

This dataset contains question-answering examples about the subject matter, permitted field of use, territorial scope, exclusivity, sublicensing, and reserved rights in licensing agreements. Each example links the answer to the source clause and a retrievable location, with key grant attributes and an answerability label. It supports training and evaluating systems that retrieve contractual evidence and answer questions from the provided text.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer grounded in the supplied contract clause. |
| question | string | A natural-language question about rights granted or retained under the licensing agreement. |
| answerable | boolean | Indicates whether the supplied contract clause contains enough information to answer the question. |
| exclusivity | string | The stated exclusivity status and any relevant limits or conditions of the grant. |
| evidence_quote | string | The exact or near-exact source passage that supports the answer. |
| reserved_rights | string | Rights expressly retained by the licensor or excluded from the grant. |
| licensed_subject | string | The work, product, technology, or other subject matter covered by the grant, when specified. |
| evidence_location | string | A retrievable source locator, such as a section number, clause heading, or page reference. |
| territorial_scope | string | The geographic area in which the granted rights may be exercised. |
| sublicensing_rights | string | Whether the licensee may grant sublicenses and any conditions that apply. |
| contract_clause_text | string | The source licensing clause or contract excerpt used to answer the question. |
| permitted_field_of_use | string | The industries, activities, or uses for which the licensee is authorized to use the licensed subject. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

