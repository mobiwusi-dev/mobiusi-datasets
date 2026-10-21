---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Procurement Approval Authority and Routing Validation Benchmark
---

# Procurement Approval Authority and Routing Validation Benchmark

This benchmark organizes procurement requests, amount bands, organizational authority rules, and candidate approval paths in JSON, alongside verifiable rule-applicability, required-chain, and path-validation results. Designed for procurement and spend management workflows, it helps assess whether approvers and approval sequences comply with authorization constraints. Use it to train or evaluate models with reinforcement learning from verifiable rewards (RLVR), using rule-check outcomes as reward signals.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| authority_rules | object | Organizational approval rules defining applicable scopes, amount bands, required roles, and approval sequence. |
| routing_evaluation | object | Evaluation results covering rule applicability, the required approval chain, candidate-path validation, and the associated reward signal. |
| procurement_request | object | The procurement request and relevant organizational and purchasing details used to determine its approval route. |
| candidate_approval_paths | array | Proposed approval paths to validate against the procurement request and applicable authority rules. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

