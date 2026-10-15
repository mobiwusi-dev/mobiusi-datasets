---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Contract Dispute Fact Verification Dataset
---

# Commercial Contract Dispute Fact Verification Dataset

This dataset centers on factual claims in commercial contract disputes and their related legal documents, covering issues such as contract performance, breach, notice, and payment. It includes evidence materials such as contract text, amendments, notices, and pleadings, with labels indicating whether a claim is supported, refuted, or insufficiently evidenced, alongside evidence spans, contradictions, missing materials, and confidence scores. It is designed for legal text analysis, contract dispute evidence review, and training or evaluating fact verification models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The contract performance, breach, notice, payment, or other disputed factual statement to be verified. |
| review_notes | string | Additional notes on annotation boundaries, document interpretation, or evidence selection. |
| claim_category | string | The factual claim category assigned based on the subject of the dispute. |
| claim_subjects | array | Key matters, obligations, or disputed objects identified in the factual claim. |
| evidence_spans | array | Specific text excerpts from legal documents used to support or refute the factual claim. |
| document_bundle | array | Contracts, amendments, notices, pleadings, and other related legal documents used to verify the claim. |
| confidence_score | number | A numerical estimate of the reliability of the verification outcome, ranging from 0 to 1. |
| missing_evidence | array | Evidence gaps or additional materials needed for a more complete verification of the claim. |
| normalized_claim | object | A structured representation of the parties, actions, objects, amounts, and deadlines in the factual claim. |
| evidence_coverage | object | A structured assessment of coverage by supporting evidence, refuting evidence, and relevant contract clauses. |
| assessment_summary | string | A summary of how the documentary evidence supports, refutes, or fails to establish the factual claim. |
| verification_label | string | The assessment of whether the related legal documents support, refute, or insufficiently evidence the factual claim. |
| contradiction_points | array | Conflicts, contradictions, or mismatches between the factual claim and the legal documents. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

