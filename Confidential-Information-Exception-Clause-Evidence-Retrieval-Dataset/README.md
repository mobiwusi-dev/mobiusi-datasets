---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Confidential Information Exception Clause Evidence Retrieval Dataset
---

# Confidential Information Exception Clause Evidence Retrieval Dataset

This dataset focuses on exceptions to confidentiality obligations, covering information that is publicly available, already known, independently developed, or lawfully obtained from a third party. It includes scenario-based retrieval questions, evidence excerpts, and source information, organized around exception criteria, proof requirements, and limits of applicability. The data supports legal authority retrieval, evidence assessment, and knowledge grounding for retrieval-augmented generation systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_record | object | Preserves the original categories, clauses, questions, evidence, and source information needed for exception-clause evidence retrieval. |
| boundary_analysis | object | Analyzes the applicability conclusion, boundary conditions, and potential risks of an exception clause in the given scenario. |
| exception_elements | array | Exception criteria, legal effects, and factual indicators extracted from clauses and evidence. |
| proof_requirements | array | Matters to prove, acceptable evidence, verification methods, and current support status summarized from clauses, questions, and evidence. |
| evidence_assessment | object | Evaluates the relevance, sufficiency, and probative role of evidence excerpts in relation to retrieval questions and exception clauses. |
| retrieval_annotation | object | Converts scenario-based questions into intent, keywords, and answer priorities for retrieval and knowledge grounding. |
| normalized_exception_type | string | The confidentiality exception type normalized from the original clause content. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

