---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Source Code Management API Authorization Constraint Verification Benchmark
---

# Source Code Management API Authorization Constraint Verification Benchmark

This benchmark covers APIs for source code management platforms, providing endpoint specifications, security schemes, declared scopes, and applicable authorization rules, together with cases that satisfy or conflict with those constraints. Each case includes expected constraint status, authorization decision, operation class, and relevant violation location or rule reference for comparison during evaluation. It supports testing whether models can verify authorization requirements for read, write, and administrative operations against the specifications and rules, and identify conflicts and violations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| constraint_case | string | The benchmark scenario or constraint assertion to evaluate, encoded as JSON text. |
| authorization_rules | string | The applicable authorization rules, encoded as JSON text and describing requirements for read, write, or administrative operations. |
| expected_rule_reference | string | The identifier or location of the rule expected to determine the authorization outcome; use an empty string when no specific rule applies. |
| expected_operation_class | string | The operation category identified for the case. |
| api_endpoint_specification | string | The source API specification for the endpoint, encoded as JSON text and including its method, path, security schemes, and declared scopes. |
| expected_constraint_status | string | The expected assessment of whether the authorization constraints are satisfied or conflict. |
| expected_violation_location | string | The expected location of the relevant authorization constraint in the specification, rule set, or test case; use an empty string when no violation is expected. |
| expected_authorization_decision | boolean | Whether the operation is expected to be authorized under the endpoint specification and applicable rules. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

