---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Dentistry Clinical Judgment Consistency Benchmark Dataset
---

# Pediatric Dentistry Clinical Judgment Consistency Benchmark Dataset

This JSON dataset organizes pediatric dental cases alongside equivalent rephrasings, repeated questions, and other wording variants, with structured responses covering diagnosis, preventive advice, and treatment plans. It evaluates whether a model maintains consistent answers when faced with clinically equivalent questions, supporting automated evaluation and quality checks for pediatric dentistry question-answering systems. Its case inputs, model responses, and consistency assessments make it easier to identify answer differences across question variants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_inputs | object | Original pediatric dental case details and question variants supplied as evaluation inputs. |
| model_answers | array | Structured model responses paired with the corresponding question variants. |
| consistency_assessment | object | Structured evaluation of whether clinically equivalent question variants receive equivalent answers. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

