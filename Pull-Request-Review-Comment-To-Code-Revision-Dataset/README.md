---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pull Request Review Comment to Code Revision Dataset
---

# Pull Request Review Comment to Code Revision Dataset

This dataset focuses on the pull request review workflow in software repositories, covering natural-language review comments, the code under discussion, repository and revision context, and the corresponding patches and revised code. Each example links review feedback to a targeted code change and may include a summary explaining the revision. It supports supervised fine-tuning of code generation models, review assistance, and evaluation of automated code repair.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| patch_diff | string | The targeted code change addressing the review comment, represented as a unified diff when possible. |
| code_context | string | The original code under discussion, with enough surrounding lines to understand and apply the review request. |
| revised_code | string | The resulting code after applying the generated patch to the supplied code context. |
| change_summary | string | A concise explanation of how the revision addresses the review comment. |
| review_comment | string | The natural-language pull request review comment specifying the requested code change. |
| repository_context | string | Repository and revision details, file paths, and other information needed to interpret the review comment, stored as a JSON-encoded string. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

