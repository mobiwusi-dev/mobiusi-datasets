---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Litigation Motion Record Fact Verification Dataset
---

# Commercial Litigation Motion Record Fact Verification Dataset

This dataset organizes factual claims from summary judgment, dismissal, and evidence-exclusion motions, along with related opposition filings, for verification against the case record. Each record can include the original and normalized claim, supporting materials such as declarations, deposition excerpts, exhibit lists, or attachments, and labels for claim category, three-way verification status, assessment, and confidence. It supports legal fact-verification model training and evaluation, litigation document review, and case-record evidence analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_category | string | The primary category assigned based on the content of the factual claim. |
| record_evidence | object | Original case-record materials used to verify the claim, such as declarations, deposition excerpts, exhibit lists, and attachments. |
| confidence_score | number | A numeric estimate of the reliability of the verification outcome, ranging from 0 to 1. |
| motion_statement | string | The original factual statement extracted from a summary judgment, dismissal, or evidence-exclusion motion, or a related opposition filing, for verification. |
| normalized_claim | string | A normalized version of the motion statement that removes redundancy and standardizes references to parties and time without changing its meaning. |
| verification_status | string | The three-way verification outcome assigned to the factual claim based on the case-record materials. |
| verification_assessment | object | An explanation of the record evidence that supports or contradicts the claim, along with any unresolved questions in the available record. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

