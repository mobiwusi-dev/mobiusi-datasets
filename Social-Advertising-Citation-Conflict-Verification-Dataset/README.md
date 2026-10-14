---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Social Advertising Citation Conflict Verification Dataset
---

# Social Advertising Citation Conflict Verification Dataset

This dataset pairs synthetic social media advertising claims with multiple source citations, including cases where citations agree, partially conflict, differ in scope, or cannot be reconciled. Each record includes the claim, source citations, per-citation evidence analyses, pairwise citation relationships, a conflict count, and an overall assessment of evidential support. It supports training and evaluation for multi-source knowledge grounding, citation verification, advertising fact-checking, and claim support assessment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| ad_claim | string | Synthetic social advertising claim to be verified. |
| citations | array | Multiple original citations corresponding to the advertising claim, including source information. |
| conflict_count | integer | Count of citation relationships identified as partially conflicting, irreconcilable, or otherwise materially inconsistent. |
| conflict_pairs | array | Pairwise analysis of agreement, conflict, scope differences, and whether conclusions from citations can be reconciled. |
| citation_analyses | array | Analysis of each citation's stance, scope of support, evidence strength, and limitations in relation to the advertising claim. |
| overall_assessment | object | Final judgment on whether the advertising claim is adequately supported, based on all citations and their relationships. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

