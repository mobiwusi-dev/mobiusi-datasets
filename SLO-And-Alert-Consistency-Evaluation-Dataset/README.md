---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SLO and Alert Consistency Evaluation Dataset
---

# SLO and Alert Consistency Evaluation Dataset

This dataset organizes SLO/SLI definitions, time-window measurements, threshold configurations, and alert states as JSON, with cases covering both consistent and inconsistent relationships among configured rules, observed results, and alert outcomes. Each record includes the expected alert state, whether the SLO target was met, an overall consistency judgment, the primary mismatch type, and an evaluation explanation. It supports assessment of a model's ability to verify service objectives, metrics, and alert rules, as well as quality evaluation in application performance management and observability workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| benchmark_case | object | The original JSON input for a single SLO and alert consistency case. |
| slo_target_met | boolean | Whether the observed SLI measurement satisfies the defined SLO target. |
| consistency_status | string | The overall adjudicated consistency result for the SLO, SLI, threshold configuration, and observed alert. |
| expected_alert_state | string | The alert state expected from the observed SLI values and configured threshold rules. |
| primary_mismatch_type | string | The main category of inconsistency identified, or none when the case is consistent. |
| evaluation_explanation | string | A concise explanation of how the SLO, observed measurements, threshold rules, and alert state support the adjudicated result. |
| alert_state_matches_expected | boolean | Whether the observed alert state agrees with the state implied by the measurements and alert configuration. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

