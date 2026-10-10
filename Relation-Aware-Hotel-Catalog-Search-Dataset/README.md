---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Relation-Aware Hotel Catalog Search Dataset
---

# Relation-Aware Hotel Catalog Search Dataset

This dataset contains matching examples that pair user lodging search queries with hotel and accommodation catalog entries. Catalog content covers hotels, room types, amenities, locations, and policies, along with relationships among these entities. Match labels, relevance scores, relation evidence, and decision rationales support training, retrieval evaluation, and error analysis for accommodation search in online travel booking engines.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| user_query | string | Lodging search text submitted by the user. |
| match_label | string | Overall match judgment between the query and the catalog entry. |
| catalog_entry | object | The original hotel or accommodation catalog record to be matched against the user query. |
| relevance_score | number | A relevance score based on the query, catalog information, and relationships among them. |
| matched_relations | array | Query-to-catalog entity relationship evidence supporting the match decision. |
| decision_rationale | string | A brief explanation of the overall match result and its key relation evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

