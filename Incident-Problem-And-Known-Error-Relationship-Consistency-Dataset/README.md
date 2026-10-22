---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Incident, Problem, and Known Error Relationship Consistency Dataset
---

# Incident, Problem, and Known Error Relationship Consistency Dataset

This JSON dataset contains IT service management incident records, problem records, and known error entries, along with their cross-record references. It covers consistency issues such as missing references, mismatched related objects, and conflicting resolution statuses, supporting evaluation of a model's ability to detect relationship errors across records. Typical uses include problem record audits, operations workflow quality assessment, and consistency-checking evaluations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| assessment | object | Computed assessment of record references, association agreement, and status consistency. |
| source_records | object | Original incident, problem, and known error records supplied for consistency checking. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

