---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Web Session and Token Security Configuration Schema Dataset
---

# Web Session and Token Security Configuration Schema Dataset

This dataset contains semi-structured Web application configurations for sessions, cookies, and tokens, mapped to a unified schema. The extracted information covers lifetimes, signing and algorithm requirements, cookie security attributes, and other explicitly stated constraints. Its structured-output SFT examples support training and evaluating models that identify security requirements in application configurations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| config_source | string | Original semi-structured application configuration containing session, cookie, or token settings. |
| token_configuration | object | Extracted token lifetime, signing, and algorithm requirements. |
| cookie_configuration | object | Extracted cookie security attributes and lifetime settings. |
| explicit_constraints | array | Additional explicit session, cookie, or token security constraints not represented by the dedicated fields. |
| session_configuration | object | Extracted session lifetime and related session requirements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

