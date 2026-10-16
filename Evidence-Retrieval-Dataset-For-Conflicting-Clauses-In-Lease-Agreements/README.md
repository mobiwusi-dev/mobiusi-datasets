---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Evidence Retrieval Dataset for Conflicting Clauses in Lease Agreements
---

# Evidence Retrieval Dataset for Conflicting Clauses in Lease Agreements

This dataset contains challenging retrieval examples from lease agreements and related legal documents, covering version differences, exceptions, rules of precedence, amendment overrides, and apparent contradictions. Each example is organized around the original query, contract context, candidate evidence, conflict analysis, controlling-evidence decisions, and retrieval supervision labels. It supports RAG retrieval training and evaluation, legal evidence ranking, and lease dispute analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | The original query, contract context, and candidate evidence for a lease clause conflict retrieval task. |
| retrieval_labels | object | Ranking, positive-example, and hard-negative labels for training or evaluating retrieval systems. |
| conflict_analysis | object | Identifies clause conflicts and applicable resolution rules based on the original contract text and candidate evidence. |
| controlling_evidence | object | Marks the evidence with greater controlling effect among conflicting candidates while preserving necessary context. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

