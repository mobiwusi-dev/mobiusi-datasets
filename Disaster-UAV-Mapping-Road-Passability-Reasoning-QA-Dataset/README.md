---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Disaster UAV Mapping Road Passability Reasoning QA Dataset
---

# Disaster UAV Mapping Road Passability Reasoning QA Dataset

This dataset uses textual observations from drone mapping, including road, bridge, flooding, and blockage conditions, together with explicit rules for determining whether a road or route is passable. Each question requires a model to apply the rules to the mapped facts, infer an access status, and explain the basis for its judgment. It supports training and evaluation of road-passability reasoning for emergency road assessment, route analysis, and rescue planning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | A question asking for a passability judgment about a road or route based on the supplied facts and rules. |
| reasoning | string | A concise explanation connecting the relevant mapping facts to the applicable access rules and resulting judgment. |
| access_rules | string | Explicit criteria for determining road or route passability from the mapped conditions. |
| mapping_facts | string | Textual observations derived from drone mapping, including road, bridge, flooding, and obstruction conditions. |
| passability_judgment | string | The inferred access status of the queried road or route, such as passable, impassable, or conditionally passable. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

