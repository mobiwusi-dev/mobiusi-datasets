---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Urban Regeneration Policy and Funding Event Extraction Dataset
---

# Urban Regeneration Policy and Funding Event Extraction Dataset

This dataset contains news articles about urban regeneration policy announcements, planning requirements, funding arrangements, project applications, and implementation timelines. It annotates article publication dates, policy and funding events, and temporal relationships between events. It supports structured analysis of urban regeneration governance and reconstruction of policy implementation timelines; the actual dataset size and time coverage depend on the delivered version.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| events | array | Policy, planning, funding, application, or implementation events extracted from the article, listed chronologically when dates are available. |
| event_relationships | array | Explicit or text-supported ordering relationships between events in the extracted timeline. |
| source_article_text | string | The original news article text provided as input for event extraction. |
| article_publication_date | string | The publication date stated in the article, normalized to ISO 8601 when available; null if not stated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

