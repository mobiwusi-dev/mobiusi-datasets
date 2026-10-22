---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Regional Practice Comparison QA Dataset for Traditional Festivals and Rituals
---

# Regional Practice Comparison QA Dataset for Traditional Festivals and Rituals

This collection contains question-and-answer examples comparing accounts of the same festival or similar rituals across regions, including differences in participation, ritual steps, terminology, and other practices. Each answer links specific claims to the relevant regional sources and keeps conclusions within the limits of the supplied evidence. It is designed for domain-specific fine-tuning, cultural knowledge QA, and evaluation of evidence-grounded responses.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct answer that distinguishes documented regional practices and does not present a local account as a universal custom. |
| source_bundle | string | Original source material with regional descriptions, excerpts, and any available references for the festival or ritual being compared. |
| scope_limitation | string | A note identifying evidence gaps, uncertainty, or limits and clarifying that the described practices apply only to the documented sources or regions. |
| comparison_question | string | A question comparing participation, ritual steps, terminology, or other practices documented in the supplied regional sources. |
| comparison_dimension | string | The main aspect addressed by the question, such as participation, sequence, terminology, or local variation. |
| evidence_attributions | array | Mappings that link each substantive claim in the answer to the supporting region and source material. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

