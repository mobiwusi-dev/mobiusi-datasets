---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Decorative Arts Materials and Making Techniques Question-Answer Dataset
---

# Decorative Arts Materials and Making Techniques Question-Answer Dataset

This dataset presents question-answer pairs about the materials and making techniques of decorative arts objects, as well as how those details are recorded in collection sources such as catalogue entries, craft descriptions, and collection literature. Each answer is linked to textual evidence, with relevant unverified details identified to help distinguish supported claims from unsupported inferences. It can support training and evaluation of domain-specific question-answering models and source-grounded knowledge retrieval.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise response limited to claims supported by the supplied source text. |
| evidence | array | One or more excerpts that directly support the answer, with source locators when available. |
| question | string | A question about materials, making techniques, or how these details are recorded, answerable from the supplied source text. |
| source_text | string | The catalogue entry, craft description, or collection literature passage used as the basis for the question and answer. |
| unsupported_details_note | string | A brief note identifying relevant details not established by the source, or an empty string when no qualification is needed. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

