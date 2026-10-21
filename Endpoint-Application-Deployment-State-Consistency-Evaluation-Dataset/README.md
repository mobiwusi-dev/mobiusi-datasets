---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Endpoint Application Deployment State Consistency Evaluation Dataset
---

# Endpoint Application Deployment State Consistency Evaluation Dataset

This JSON dataset covers application catalogs, deployment assignments, target versions, and endpoint software inventories across application release and endpoint software management workflows. Comparing intended deployment states with software actually installed on devices helps identify version mismatches, conflicts between assignments and inventories, and stale deployment status information. It supports the evaluation and improvement of endpoint software deployment consistency checks and automated assessment workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| consistency_summary | object | Computed counts and an overall assessment for the deployment snapshot. |
| deployment_findings | array | Actionable discrepancies and stale-state observations identified by comparing deployment data. |
| deployment_snapshot | object | The original JSON input containing the application catalog, deployment assignments, and endpoint software inventory. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

