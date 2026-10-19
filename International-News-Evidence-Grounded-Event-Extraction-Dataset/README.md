---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: International News Evidence-Grounded Event Extraction Dataset
---

# International News Evidence-Grounded Event Extraction Dataset

This dataset pairs international news reports with corresponding JSON event structures covering attributes such as event type, participants, time, and location. Extracted attributes are linked to supporting text spans or locations in the source article. It supports training and evaluating models to extract events from news, produce structured outputs, and provide traceable evidence, making it useful for structured-output SFT, news analysis, and event knowledge base construction.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| events | array | Events identified in the article, with extracted attributes linked to supporting text evidence. |
| article_text | string | The original international news report used as the input source. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

