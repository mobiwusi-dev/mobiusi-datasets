---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Learning Text Fact and Event Extraction Dataset
---

# Korean Learning Text Fact and Event Extraction Dataset

This dataset pairs short passages for Korean reading practice with corresponding JSON annotations. The annotations capture people, places, and events explicitly mentioned in the text, including event times, participants, locations, supporting text, and explicitly stated relations. It supports training models to extract facts from Korean passages and produce structured outputs, as well as reading comprehension practice, information extraction evaluation, and educational tool development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| events | array | Events described in the passage, including their explicit time, participants, location, and supporting text. Use an empty array if none are described. |
| people | array | People explicitly mentioned in the passage. Use an empty array if none are mentioned. |
| places | array | Places explicitly mentioned in the passage. Use an empty array if none are mentioned. |
| relations | array | Relations between people, places, or events that are explicitly expressed in the passage. Use an empty array if none are stated. |
| source_text | string | The original Korean passage to be analyzed. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

