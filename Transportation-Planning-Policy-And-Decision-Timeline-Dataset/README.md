---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Transportation Planning Policy and Decision Timeline Dataset
---

# Transportation Planning Policy and Decision Timeline Dataset

This dataset is built from news about transportation policies, planning proposals, and related public decisions. Each record captures the source text, article title and publication date, along with the policy name, category, geographic scope, decision summary, and extracted events. Events such as proposal announcements, public consultations, approvals, revisions, implementation, and termination are ordered chronologically to support traceable decision analysis, event extraction, and structured-output model training and evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| events | array | Extracted policy and public decision events, ordered from earliest to latest. |
| policy_name | string | The name of the transportation policy, plan, or proposal discussed in the article. |
| source_text | string | The original news text used as input for event extraction. |
| source_title | string | The article title identified in the source text, when available. |
| policy_category | string | The main transportation planning category, such as public transit, road infrastructure, active travel, or land use and transport integration. |
| decision_summary | string | A concise summary of the policy decision and its current status based on the article. |
| geographic_scope | string | The city, region, corridor, or other geographic area covered by the policy or plan. |
| source_publication_date | string | The publication date identified in the article, preferably in ISO 8601 format when available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

