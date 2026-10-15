---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Contradictory Case File Evidence Retrieval Benchmark
---

# Contradictory Case File Evidence Retrieval Benchmark

Designed for fact verification in commercial litigation, this benchmark pairs query claims with legal document excerpts that support, contradict, or only superficially relate to the issue in dispute. Annotations identify evidence relationships and counterevidence types, with source metadata, source anchors, and rationale. The data supports evaluation of whether models can find meaningful evidence among similar or conflicting narratives, assess whether a claim is undermined, and trace conclusions to the relevant case file.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_claim | string | A commercial litigation fact or legal claim to be retrieved and verified. |
| source_anchor | string | A concise citation, key sentence, or verifiable location note that anchors the judgment to its case file source. |
| relation_label | string | The primary evidence relationship between the candidate excerpt and the query claim. |
| source_metadata | object | Case, document, and original-text location information associated with the candidate excerpt. |
| is_claim_refuted | boolean | Indicates whether the candidate excerpt directly or materially weakens or refutes the query claim. |
| candidate_excerpt | string | A candidate evidence passage retrieved from a case file document for assessing the query claim. |
| annotation_rationale | string | Explains the semantic relationship between the excerpt and query claim, including the point of conflict or lack of sufficient support. |
| counterevidence_type | string | The specific type of counterevidence represented by the excerpt, such as refutation, conflicting account, or insufficient support. |
| annotation_confidence | number | A score from 0 to 1 representing overall confidence in the evidence relation, counterevidence type, and source anchoring judgments. |
| retrieval_relevance_score | number | A score from 0 to 1 indicating the candidate excerpt's evidentiary relevance to the query claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

