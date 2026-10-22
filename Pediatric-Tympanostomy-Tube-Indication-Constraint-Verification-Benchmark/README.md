---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Tympanostomy Tube Indication Constraint Verification Benchmark
---

# Pediatric Tympanostomy Tube Indication Constraint Verification Benchmark

This structured JSON benchmark records pediatric case facts such as middle ear effusion, recurrent otitis media, hearing impact, and relevant history, alongside candidate tympanostomy tube recommendations and applicable indication rules. It covers case facts, rule-by-rule checks, recommendation status, missing evidence, unmet constraints, and an overall assessment, enabling evaluation of whether a model can determine if a recommendation is supported by the case. It is intended for pediatric otolaryngology model evaluation and clinical decision support research, not as a substitute for professional medical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_facts | object | Patient and clinical facts recorded for evaluating tympanostomy tube candidacy. |
| criterion_checks | array | Rule-by-rule assessment of the candidate recommendation against the case facts. |
| indication_rules | object | The indication criteria and constraints to apply when evaluating the candidate recommendation. |
| missing_evidence | array | Information needed to assess the recommendation that is absent or insufficiently documented. |
| unmet_constraints | array | Applicable indication requirements or constraints that the case does not satisfy. |
| overall_assessment | string | Concise explanation of the recommendation status, including relevant evidence, missing support, and unmet constraints. |
| recommendation_status | string | Overall determination of whether the candidate recommendation is supported by the case facts and applicable rules. |
| candidate_tube_recommendation | string | The proposed recommendation regarding tympanostomy tube placement, including any stated timing or laterality. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

