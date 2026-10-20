---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Floodplain Planning and Regulatory Q&A Dataset
---

# Floodplain Planning and Regulatory Q&A Dataset

This dataset contains expert question-and-answer text based on floodplain planning policies, land development guidance, and flood protection regulations. Each record uses a source text to identify relevant provisions and address applicability requirements, development restrictions, exceptions, and compliance grounds. It supports knowledge retrieval, open-book question answering, and evaluation of retrieval-augmented generation systems for flood risk planning and management.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise response to the question based on the supplied source text. |
| question | string | The question to be answered by locating and interpreting relevant provisions in the source text. |
| exceptions | string | Any exceptions, exemptions, or special cases relevant to the question, or an explicit statement that none are identified. |
| source_text | string | The professional policy, guidance, or regulatory text used as the evidence source for the answer. |
| cited_provisions | string | The section numbers, clause identifiers, or quoted passages that support the answer. |
| compliance_basis | string | The regulatory or policy rationale establishing how the answer supports compliance or identifies a compliance obligation. |
| restriction_conditions | string | The relevant restrictions, thresholds, conditions, or prohibitions stated in the source text. |
| applicability_requirements | string | The situations, locations, activities, or development types to which the cited requirements apply. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

