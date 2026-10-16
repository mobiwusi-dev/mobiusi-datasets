---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Particle Usage Evidence Retrieval Dataset
---

# Korean Particle Usage Evidence Retrieval Dataset

This dataset organizes structured records from Korean particle teaching webpages, connecting learner questions and target particles with candidate explanations and source-text evidence. It covers uses such as subject, object, topic, location, direction, and coordination particles, with explicit links showing whether evidence supports, qualifies, supplements, or refutes an explanation. It is designed for Korean grammar retrieval, evidence-grounded question answering, and language-learning tools.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_page | object | Original Korean particle teaching webpage content used as the basis for extraction and evidence linking. |
| evidence_items | array | Source excerpts from teaching webpages that support, qualify, supplement, or refute candidate explanations. |
| evidence_links | array | Explicit relationships between candidate explanations and webpage evidence, including support, qualification, counterexample, and supplementation. |
| particle_forms | array | Korean particle forms mentioned in the question or evidence, such as 이/가, 은/는, 을/를, 에, 에서, 으로/로, and 와/과. |
| learner_question | string | A question derived from the page about differences in Korean particle functions or conditions of use. |
| particle_functions | array | Syntactic, semantic, or pragmatic functions expressed by the target particles. |
| quality_assessment | object | A derived assessment of whether the record covers particle contrasts, usage conditions, and exceptions. |
| retrieval_keywords | array | Keywords for retrieving similar particles, function contrasts, usage conditions, and exceptions. |
| candidate_explanations | array | Explanations of particle usage generated or extracted for the learner question; each may be supported, qualified, or refuted by different webpage evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

