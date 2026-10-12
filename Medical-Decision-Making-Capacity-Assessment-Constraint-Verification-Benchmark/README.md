---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Medical Decision-Making Capacity Assessment Constraint Verification Benchmark
---

# Medical Decision-Making Capacity Assessment Constraint Verification Benchmark

This benchmark presents structured JSON cases containing specific medical decisions, patient interview evidence, clinical context, and claimed decision-making capacity assessments to be verified. Cases focus on the elements required for each decision, enabling evaluation of whether conclusions are supported by the evidence and whether material information gaps or conflicts are identified. It is designed for model evaluation, constraint reasoning research, and clinical AI validation in consultation-liaison psychiatry.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence_gaps | array | Material information missing from the record that prevents or limits validation of the assessment. |
| overall_result | string | The overall judgment on whether the claimed assessment is supported by the available decision-specific evidence. |
| clinical_context | object | Relevant clinical and communication information for interpreting the interview evidence. |
| decision_context | object | The medical decision being considered and the stakes specific to that decision. |
| constraint_checks | array | Explicit checks of whether the proposed assessment follows the constraints of a decision-specific capacity evaluation. |
| overall_rationale | string | A concise synthesis of the required elements, constraint checks, evidence gaps, and conflicts supporting the overall result. |
| required_elements | array | Decision-specific capacity elements and an evidence-based assessment of whether each element is addressed. |
| claimed_assessment | object | The capacity determination and supporting rationale to evaluate against the specific decision and interview evidence. |
| evidence_conflicts | array | Material contradictions among the interview evidence, clinical context, and claimed assessment. |
| interview_evidence | array | Patient statements and observations from the interview that may support or challenge capacity elements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

