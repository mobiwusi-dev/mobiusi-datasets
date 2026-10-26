---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: PON Shared Fault Scope Inference Q&A Dataset
---

# PON Shared Fault Scope Inference Q&A Dataset

This text-based dataset presents multiple ONT cases with service states, access topology, and fault timelines, covering shared PON branch or upstream faults, isolated subscriber faults, and mixed scenarios. Each question asks the model to compare cases, identify evidence that supports or weakens a shared-fault hypothesis, and explain its reasoning and confidence. It supports fault-scope analysis, inductive reasoning training, and evaluation for FTTH operations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| confidence | number | Confidence in the scope assessment, represented as a value from 0 to 1. |
| case_comparison | string | Comparison of the relevant service states, topology relationships, and fault timing across the cases. |
| case_bundle_text | string | Text containing multiple ONT service-status cases, access topology, fault timelines, and the question to be answered. |
| scope_assessment | string | Comparative assessment of whether the cases most likely indicate a shared PON branch or upstream issue, independent subscriber faults, or a mixture. |
| inference_rationale | string | Reasoning that connects the observed evidence to the scope assessment and distinguishes strong signals from ambiguous evidence. |
| shared_outage_indicators | string | Evidence patterns across cases that support a shared PON branch or upstream component issue. |
| single_subscriber_indicators | string | Evidence patterns that are more consistent with an isolated subscriber or premises fault. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

