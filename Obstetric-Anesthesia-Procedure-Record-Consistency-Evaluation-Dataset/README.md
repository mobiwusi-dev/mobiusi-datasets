---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Obstetric Anesthesia Procedure Record Consistency Evaluation Dataset
---

# Obstetric Anesthesia Procedure Record Consistency Evaluation Dataset

This evaluation dataset contains obstetric anesthesia procedure records serialized as JSON text, covering anesthesia methods, procedure details, obstetric management, and related documentation, with a label indicating whether each record is internally consistent. For records containing contradictions, it provides the relevant field locations and explanations, enabling evaluation of a model's ability to detect and localize conflicts against the reference annotations. It supports model evaluation, quality assurance, and benchmark comparisons for consistency checking in obstetric anesthesia records.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| conflicts | array | Reference conflicts identified within the source record, including relevant field locations and explanations. An empty array indicates that no conflict was identified. |
| is_consistent | boolean | Indicates whether the source record is internally consistent across its relevant fields. |
| source_record | string | The original obstetric anesthesia procedure record serialized as JSON text, including the anesthesia method, procedure details, obstetric management, and related documentation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

