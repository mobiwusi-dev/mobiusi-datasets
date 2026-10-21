---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: International News Conflict Reporting Evidence Mapping Dataset
---

# International News Conflict Reporting Evidence Mapping Dataset

This dataset covers disputed events in international news and captures claims from different reports that differ or have not been independently corroborated. Its JSON records extract claims by source, link them to the originating reports and supporting evidence, and label relationships between claims without merging accounts or deciding which claims are true. It supports training and evaluation of structured information extraction systems that preserve source differences and trace evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_reports | array | Original reports provided as independent sources for extracting claims. |
| claim_relations | array | Pairwise labels describing relationships between claims from different reports or reporting contexts. These labels do not determine which claim is true. |
| extracted_claims | array | Claims attributed to individual reports and linked to their source report and supporting evidence. Claims remain separate rather than being combined into one account. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

