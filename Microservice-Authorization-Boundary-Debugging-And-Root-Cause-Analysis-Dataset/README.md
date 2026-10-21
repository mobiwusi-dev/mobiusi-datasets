---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Microservice Authorization Boundary Debugging and Root-Cause Analysis Dataset
---

# Microservice Authorization Boundary Debugging and Root-Cause Analysis Dataset

This dataset contains microservice source-code cases involving flaws in identity propagation, permission checks, and tenant-isolation boundaries, with supporting details on service boundaries, identity flows, failure stages, and root causes. Each case also includes security impact, a repair explanation, fixed code, and regression test guidance for cloud-native application security reviews and authorization troubleshooting. It supports code SFT by helping models reason from source code and call chains to locate authorization failures and propose fixes.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| fixed_code | string | A corrected code snippet addressing the flaw in the source code. |
| root_cause | string | Explains the code logic, trust assumption, or omitted check that caused the authorization boundary to fail. |
| source_code | string | A microservice source-code snippet containing an authorization boundary flaw, provided as the input for analysis. |
| failure_stage | string | Specifies whether the failure occurs during identity extraction, identity propagation, permission evaluation, or a downstream call. |
| identity_flow | string | Describes how an identity or credential travels from the request entry point through the call chain to the permission check. |
| regression_test | string | Describes test scenarios for validating the fix and the expected authorization or tenant-isolation outcomes. |
| security_impact | string | Describes potential consequences such as unauthorized access, privilege escalation, or cross-tenant data exposure. |
| service_boundary | string | Describes the relevant service, interface, or component boundaries and their roles in the call chain. |
| repair_explanation | string | Explains how the fix strengthens identity propagation, permission validation, or tenant boundary checks. |
| authorization_check_point | string | Identifies the function, call site, or code stage where an authorization check should occur or currently occurs. |
| tenant_isolation_analysis | string | Explains whether the flaw enables cross-tenant access and how tenant identifiers are handled during validation and data access. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

