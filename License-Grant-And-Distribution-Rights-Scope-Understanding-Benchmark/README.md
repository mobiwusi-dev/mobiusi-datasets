---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: License Grant and Distribution Rights Scope Understanding Benchmark
---

# License Grant and Distribution Rights Scope Understanding Benchmark

This benchmark evaluates how well models interpret rights boundaries and applicable conditions in licensing and distribution agreements, including the covered parties, products or services, territories, sales channels, exclusivity, and sublicensing restrictions. It pairs verbatim contract clauses with evaluation questions and provides structured rights-scope extraction, clause-based interpretation, boundary summaries, and uncertainty information. It supports legal document understanding evaluation, model comparison, and domain-specific validation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| rights_scope | object | Structured extraction of the parties, covered subject matter, and key dimensions of the grant. |
| source_clause | string | The verbatim contract excerpt used as the primary source for interpreting the rights grant. |
| uncertainties | array | Material ambiguities, missing context, or interpretive limitations affecting the rights analysis. |
| boundary_summary | string | A concise statement of what falls inside and outside the grant's scope. |
| evaluation_question | string | The question asking what rights are granted or how their boundaries and conditions apply. |
| rights_interpretation | string | A concise explanation of the rights granted, addressing the evaluation question and grounding the interpretation in the clause. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

