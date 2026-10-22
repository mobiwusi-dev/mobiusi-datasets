---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Contract Clause Absence and Evidence Insufficiency Verification Benchmark
---

# Contract Clause Absence and Evidence Insufficiency Verification Benchmark

This benchmark focuses on negative claims about procurement and sales agreements. It provides contract text with known document coverage; the material may be complete or partial. Each example assesses whether the available material proves that a specified right, restriction, or responsibility is absent, distinguishing proven absence from insufficient evidence, contrary evidence, and inconclusive records. It supports training and evaluating legal document verifiers for contract review, evidence assessment, and cautious reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| absence_claim | string | Negative claim asserting that the contract does not contain a specified right, restriction, or responsibility. |
| contract_text | string | Text of the supplied procurement or sales contract, which may be complete or partial. |
| document_scope | string | Known coverage of the supplied contract material. |
| evidence_spans | array | Relevant quotations or text excerpts supporting the assessment; an empty array may be used when no relevant span is available. |
| absence_assessment | string | Annotated outcome distinguishing proven absence from mere lack of evidence, contrary evidence, or an inconclusive record. |
| assessment_rationale | string | Explanation of why the available contract material does or does not establish the claimed absence, taking document scope into account. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

