---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Reexamination and Appeal Legal Evidence Retrieval Benchmark
---

# Patent Reexamination and Appeal Legal Evidence Retrieval Benchmark

This benchmark contains legal documents from patent reexamination or appeal proceedings, including appeal briefs, responses, and decisions. It defines evidence retrieval tasks around disputed issues, decision reasoning, and adopted arguments, with annotations identifying direct support in the decision text and links between arguments and evidence. It supports evaluation of evidence localization, retrieval ranking, citation accuracy, and knowledge grounding in dense patent-law reasoning, as well as the development and validation of legal retrieval-augmented generation systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence_spans | array | Gold-standard supporting evidence organized as retrievable, locatable, and comparable text spans. |
| evaluation_task | object | Input retrieval tasks focused on disputed issues, decision reasoning, or adopted arguments. |
| normalized_task | object | Standardized disputed issues and retrieval targets derived from the original task and document content. |
| gold_annotations | object | Human annotations of decision outcomes, direct supporting evidence, and adopted arguments for evaluating retrieval and evidence grounding. |
| source_documents | array | Original documents and text from patent reexamination or appeal proceedings, including appeal briefs, responses, and decisions. |
| retrieval_evaluation | object | Metrics calculated from gold-standard evidence and adopted arguments to assess system retrieval, citation, and evidence-linking performance. |
| retrieval_submission | object | Ranked results, answers, and citations submitted by a retrieval or generation system for evaluation. |
| argument_evidence_links | array | Links between adopted arguments and their direct supporting evidence for evaluating knowledge-grounding capability. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

