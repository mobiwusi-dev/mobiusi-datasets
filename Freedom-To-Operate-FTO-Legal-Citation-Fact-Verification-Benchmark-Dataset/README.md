---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Freedom-to-Operate (FTO) Legal Citation Fact Verification Benchmark Dataset
---

# Freedom-to-Operate (FTO) Legal Citation Fact Verification Benchmark Dataset

This benchmark supports fact verification in freedom-to-operate (FTO) legal analysis. It includes independently assessable atomic fact statements, cited excerpts from relevant patents and legal procedural documents, and verification labels indicating whether the evidence supports, refutes, or fails to establish each statement. Structured evidence assessments, rationales, and normalized sufficiency scores from 0 to 1 help evaluate whether models verify claims against cited materials rather than merely restating conclusions. The dataset is suited to training and evaluating legal text understanding, citation verification, and FTO analysis support systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| patent_evidence | object | Patent documents and cited excerpts that support or refute the atomic fact statement. |
| verification_label | string | The verification outcome determined by the relationship between the atomic fact statement and the cited evidence. |
| evidence_assessment | object | A structured assessment of how each factual element in the atomic fact statement corresponds to the cited excerpts. |
| atomic_fact_statement | string | A single, independently assessable factual claim in a freedom-to-operate legal analysis. |
| verification_rationale | string | Explains how the cited excerpts support, refute, or fail to establish the atomic fact statement, identifying the key legal or factual grounds. |
| legal_procedure_evidence | object | Legal procedural documents and cited excerpts relevant to the atomic fact statement. |
| evidence_sufficiency_score | number | A normalized score from 0 to 1 indicating how sufficiently the available cited materials allow verification of the atomic fact statement. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

