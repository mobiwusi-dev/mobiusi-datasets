---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Evidence-Constrained Verification Benchmark for Childhood Autism Diagnosis
---

# Evidence-Constrained Verification Benchmark for Childhood Autism Diagnosis

This benchmark presents structured JSON case evidence covering social communication, restricted and repetitive behaviors, developmental history, behavior across contexts, and functional impact, assessed against a specified diagnostic standard. Annotations capture criterion coverage, internal evidence contradictions, and key information gaps, enabling evaluation of whether models verify diagnostic constraints rather than infer from isolated features. It supports model evaluation, constraint-reasoning research, and benchmark development in developmental-behavioral pediatrics.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_record | object | Original case evidence, including developmental history, behavior across contexts, and functional impact. |
| overall_rationale | string | Concise synthesis of criterion coverage, contradictions, and key information gaps without asserting a diagnosis beyond the evaluated constraints. |
| diagnostic_standard | object | The designated standard and its explicit diagnostic requirements to be checked against the case evidence. |
| key_information_gaps | array | Important missing information that limits evaluation of the required diagnostic constraints. |
| criterion_assessments | array | Evaluations of how the case evidence relates to each required criterion. |
| internal_contradictions | array | Descriptions of material inconsistencies within or between the available case evidence items. |
| overall_constraint_status | string | Summary of whether the available evidence satisfies, partially satisfies, fails to satisfy, or cannot establish the specified diagnostic constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

