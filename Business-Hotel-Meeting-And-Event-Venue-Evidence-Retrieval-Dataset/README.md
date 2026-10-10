---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Business Hotel Meeting and Event Venue Evidence Retrieval Dataset
---

# Business Hotel Meeting and Event Venue Evidence Retrieval Dataset

This dataset brings together information from business hotel web pages about meeting rooms and event venues, including area, layout, capacity, audiovisual equipment, and supporting services. Each record links a user query with source page content, venue details, and relevant evidence snippets, making the information suitable for web-text retrieval and retrieval-augmented generation. It can support the development and evaluation of evidence retrieval and question-answering workflows for business meetings, banquets, and events.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer to the user's original query, based on the venue specifications and supporting evidence. |
| raw_query | string | The user's original question about meeting room or event venue specifications, equipment, or supporting services. |
| hotel_name | string | The name of the business hotel identified in the webpage content. |
| venue_name | string | The name of the meeting room or event venue stated on the webpage. |
| venue_type | string | The venue category or intended use, such as a meeting room, banquet hall, or multifunction room. |
| evidence_items | array | Evidence items linking venue facts to excerpts from the webpage for retrieval and answer verification. |
| source_page_url | string | The URL of the source page, extracted from the original webpage or collection record. |
| raw_webpage_html | string | Original HTML text from a business hotel meeting room or event venue webpage, provided as retrieval source material. |
| venue_specifications | object | Venue area, layout, capacity, audiovisual equipment, and supporting services extracted from the webpage. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

