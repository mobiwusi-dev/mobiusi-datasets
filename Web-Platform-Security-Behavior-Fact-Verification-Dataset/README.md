---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Web Platform Security Behavior Fact Verification Dataset
---

# Web Platform Security Behavior Fact Verification Dataset

This dataset focuses on security behavior in browsers, Web protocols, and common application frameworks, covering mechanisms such as cookies, Cross-Origin Resource Sharing (CORS), and Content Security Policy (CSP). Each record links a technical claim to evidence from official documentation or other web text, and includes a verification label, rationale, and security mechanism category. The data supports fact-verification model training and evaluation, Web application security analysis, technical knowledge validation, and evidence-tracing research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | A factual claim about security behavior in a browser, Web protocol, or application framework that requires verification. |
| source_url | string | The original URL of the webpage containing the evidence. |
| evidence_text | string | An excerpt from official documentation or other web text used to verify the claim. |
| security_mechanism | string | The Web security mechanism addressed by the claim, such as cookies, Cross-Origin Resource Sharing, or Content Security Policy. |
| verification_label | string | The judgment of whether the claim is supported by the evidence. |
| verification_rationale | string | An explanation of how the evidence relates to the claim and supports the verification judgment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

