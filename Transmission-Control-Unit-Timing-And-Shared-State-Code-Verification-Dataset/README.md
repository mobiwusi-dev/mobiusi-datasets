---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Transmission Control Unit Timing and Shared-State Code Verification Dataset
---

# Transmission Control Unit Timing and Shared-State Code Verification Dataset

Designed for transmission control unit software verification, this dataset covers source code for periodic tasks, event handling, and shared-state access, with associated timing and state constraints, verification conclusions, and supporting evidence. Samples also include issue categories, detected timing violations, shared-state consistency assessments, and root-cause explanations. Use it to evaluate whether models can identify concurrency, update-order, and state-consistency risks, and to support domain-specific evaluation and root-cause analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Plain-text source code for transmission control unit periodic tasks, event handling, or shared-state access that is subject to verification. |
| issue_category | string | Category of an issue identified during verification, or an indication that no issue was found. |
| validation_status | string | Overall conclusion of the code verification. |
| verification_evidence | string | Key code excerpts, locations, or analysis evidence supporting the verification conclusion. |
| root_cause_explanation | string | Explains the code-level cause of a verification failure or risk, including relevant concurrency, timing, or state-access mechanisms. |
| temporal_state_constraints | string | Verification constraints describing task periods, event order, shared-state read and write order, and state consistency. |
| temporal_violation_detected | boolean | Indicates whether verification identified a violation involving task periods, event handling, or state update order. |
| shared_state_consistency_assessment | string | Describes whether shared-state reads and writes remain consistent across tasks or events. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

