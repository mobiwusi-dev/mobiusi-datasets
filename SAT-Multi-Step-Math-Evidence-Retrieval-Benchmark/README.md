---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Multi-Step Math Evidence Retrieval Benchmark
---

# SAT Multi-Step Math Evidence Retrieval Benchmark

This benchmark contains SAT math problems requiring multi-step derivations, a candidate evidence library of concepts and formulas, and annotations identifying the evidence needed at each step along with complete evidence chains. It assesses whether retrieval-augmented generation systems retrieve knowledge that is both complete across the solution steps and applicable to the problem, rather than merely returning one related formula. It supports SAT math knowledge retrieval, evidence-chain evaluation, and the development of retrieval-augmented generation systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| chain_summary | object | Calculated summary statistics for the multi-step evidence chain, including its size, dependency depth, and completeness. |
| source_record | object | The original record supplied during dataset creation, containing the problem, candidate evidence library, and complete step-by-step annotations. |
| evidence_chain | array | An ordered evidence chain derived from the original step annotations, representing the complete and applicable knowledge required at each reasoning step. |
| retrieval_evaluation_target | object | A RAG retrieval evaluation target derived from the reference evidence chain, emphasizing evidence-set completeness and applicability. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

