---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Weightlifting Load Calculation and Progression Verification Dataset
---

# Weightlifting Load Calculation and Progression Verification Dataset

This dataset contains load-calculation prompts and step-by-step responses covering the snatch, clean and jerk, and related training variations. Topics include percentages of a reference maximum, load progressions, rounding, and barbell plate loading, with structured annotations for calculation steps, training-constraint compliance, and overall validity. It is designed for process-verifier training, reasoning evaluation, and the development of tools for checking weightlifting calculations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | Step-by-step calculations and response extracted from the original text. |
| prompt_text | string | Training load calculation question and constraints extracted from the original text. |
| lift_variant | string | Weightlifting lift or training variation referenced in the prompt, such as the snatch, clean and jerk, or a derivative. |
| overall_valid | boolean | True when all relevant calculations and training constraints pass validation; otherwise false. |
| plate_loading | object | Plate-loading plan for the target total weight, recorded by bar weight and plates per side. |
| target_load_kg | number | Target load calculated from or extracted using the reference maximum and target percentage. |
| reasoning_steps | array | Calculation steps in response order, including results and validation statuses for arithmetic and training constraints. |
| reference_max_kg | number | Reference maximum used for load calculations, when a value is provided in the prompt. |
| target_percentage | number | Percentage of the reference maximum specified by the prompt. |
| prompt_answer_text | string | Original text containing the training question, calculation prompt, and step-by-step response. |
| validation_summary | string | Brief summary of arithmetic correctness, constraint compliance, and major errors. |
| rounding_increment_kg | number | Weight progression, rounding, or plate-loading increment specified by the prompt. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

