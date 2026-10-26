---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Anesthesia Medication Record Consistency Benchmark
---

# Pediatric Anesthesia Medication Record Consistency Benchmark

This benchmark provides JSON examples of pediatric anesthesia medication records, covering information such as patient weight, drug dose, concentration, administration volume, route, and time. It includes internally consistent and inconsistent records, with reference consistency labels and annotated discrepancies to evaluate a model's ability to detect mismatches within a record. It is intended for automated evaluation, not for clinical prescribing or medication decisions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The original JSON medication record provided for consistency analysis. |
| evaluation_note | string | Optional benchmark guidance clarifying the scope or interpretation of the reference annotation. |
| expected_consistency | string | Reference classification of the record's internal consistency, without assessing whether the medication choice or dose is clinically appropriate. |
| expected_inconsistencies | array | Reference list of internal contradictions or mismatches for evaluation. An empty list indicates that none are identified. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

