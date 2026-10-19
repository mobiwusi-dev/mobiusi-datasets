---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Frequency Synthesizer Equation Error Localization and Correction Dataset
---

# Frequency Synthesizer Equation Error Localization and Correction Dataset

This dataset focuses on frequency synthesizer equations involving division ratios, output frequencies, and frequency steps. It contains derivations with symbolic transformation or algebraic reasoning errors, annotated with error types, step indices, and precise locations. Each record provides the incorrect and corrected expressions, a complete corrected derivation, and an explanation, supporting model training and evaluation for identifying, locating, and correcting mathematical errors in frequency synthesis. The data centers on mathematical expressions and derivation text for math supervised fine-tuning and symbolic reasoning evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| error_type | string | The category of algebraic or symbolic reasoning error in the source derivation. |
| final_result | string | The final corrected frequency synthesizer expression or computed relationship, including relevant variable definitions when needed. |
| error_location | string | The specific equation, term, symbol, or transformation where the error occurs. |
| source_derivation | string | The original frequency synthesizer problem statement and equation derivation, including the incorrect symbolic transformation. |
| corrected_derivation | string | The complete corrected equation derivation, preserving the logical sequence from the given quantities to the result. |
| corrected_expression | string | The corrected form of the erroneous equation or expression. |
| erroneous_step_index | integer | The zero-based index of the derivation step containing the error. |
| incorrect_expression | string | The erroneous equation or expression as written in the source derivation. |
| correction_explanation | string | A concise explanation of why the original transformation is invalid and how the corrected reasoning resolves the error. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

