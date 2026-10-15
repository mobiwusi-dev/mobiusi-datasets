---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Application Status Fact Verification Dataset
---

# Patent Application Status Fact Verification Dataset

This dataset pairs natural-language claims about whether a patent application has been published, is under examination, granted, abandoned, terminated, or remains active with evidence from patent office records, legal status pages, and public bibliographic information. Each example supports a judgment that the evidence supports, refutes, or does not determine the claim, and includes details such as a normalized application status, rationale, and confidence score. It is suited to training and evaluating fact verification, legal status recognition, and evidence reasoning on patent-related web text.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | A natural-language claim to verify about whether a patent application has been published, is under examination, granted, abandoned, terminated, or remains active. |
| source_url | string | The original URL of the evidence webpage or public record. |
| source_type | string | Identifies the category of the original evidence source. |
| evidence_text | string | Original evidence text from a patent office web record, legal status page, or public bibliographic record. |
| confidence_score | number | The confidence in the fact verification outcome, on a scale from 0 to 1. |
| evidence_summary | string | A concise Chinese-language summary of the evidence relevant to the claim. |
| decision_rationale | string | Explains how the evidence supports or refutes the claim, or why it is insufficient to determine the application status. |
| verification_label | string | The outcome of verifying the claim against the available evidence. |
| conflicting_evidence | boolean | Indicates whether different evidence sources contain status or date conflicts that may affect the decision. |
| normalized_application_status | string | The patent application status normalized from the claim and evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

