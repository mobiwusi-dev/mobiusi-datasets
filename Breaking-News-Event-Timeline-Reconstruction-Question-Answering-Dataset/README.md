---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Breaking News Event Timeline Reconstruction Question-Answering Dataset
---

# Breaking News Event Timeline Reconstruction Question-Answering Dataset

This dataset brings together multiple news reports or consecutive updates about the same breaking event. Its question-answer examples require linking information across texts, including times, actions, and changes in event status, and provide answers, reconstructed timelines, and supporting evidence. Samples also capture ambiguities, conflicting accounts, or unresolved details, making the collection useful for evidence-grounded multi-hop reasoning, reasoning-focused supervised fine-tuning, and evaluation of news event understanding.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise, source-grounded response to the question. |
| evidence | array | Evidence drawn from the sources to support the answer and timeline reconstruction. |
| question | string | A question that requires linking information across the source reports and updates. |
| timeline | array | Events reconstructed from the source reports and arranged in chronological order. |
| uncertainties | array | Ambiguities, conflicting reports, or unresolved details that limit the reconstruction. |
| source_reports | string | Original articles or consecutive updates about the breaking event, including available source labels and timestamps. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

