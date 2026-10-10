---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Tenant Authorization Code Verification Dataset
---

# Multi-Tenant Authorization Code Verification Dataset

This dataset contains source code snippets from cloud-native applications involving tenant identity validation, resource access control, and cross-tenant data access. The examples are labeled to indicate whether observed authorization behavior complies with the expected tenant-isolation and access boundaries, with structured details such as programming language, identity source, authorization mechanism, violation category, and supporting evidence. It is suitable for code verification training, multi-tenant security assessment, authorization flaw detection, and cloud-native security research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | string | Key code logic or a concise analysis supporting the authorization behavior and boundary-compliance conclusion. |
| source_code | string | Cloud-native application source code to be evaluated for authorization behavior. |
| expected_boundary | string | Tenant-isolation or resource-access rule that the code is expected to enforce. |
| violation_category | string | Classification of an authorization-boundary issue in the code, including the appropriate category when there is no violation or the result cannot be determined. |
| boundary_compliance | boolean | Whether the code meets the expected authorization boundary: true if compliant and false if non-compliant. |
| programming_language | string | Programming language identified from the source code. |
| tenant_identity_source | string | Source used by the code to obtain or validate the current tenant identity, such as a token claim, request context, or database record. |
| authorization_mechanism | string | Primary mechanism used by the code to determine whether a user or service may access a target resource. |
| cross_tenant_data_access | boolean | Whether the code may allow access to data belonging to another tenant. |
| observed_authorization_decision | string | Access behavior determined from the code logic. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

