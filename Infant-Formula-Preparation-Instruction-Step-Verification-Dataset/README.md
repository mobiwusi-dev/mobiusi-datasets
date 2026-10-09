---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Infant Formula Preparation Instruction Step Verification Dataset
---

# Infant Formula Preparation Instruction Step Verification Dataset

This dataset focuses on infant formula preparation and includes product-label instructions, explicit safety constraints, user questions, and complete answers based on the information supplied in each example. Answers are split into steps and annotated for adherence to the applicable label instructions and safety constraints, with overall judgments and verification notes. It supports process verifier training and evaluation, constraint verification, and related text review workflows; its judgments are limited to the instructions and constraints provided in each example and are not a substitute for professional safety assessment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_steps | array | The answer split into steps in sequence, with step-level verification results against label instructions and safety constraints. |
| user_question | string | The original question about preparing infant formula that the answer should address. |
| generated_answer | string | The complete generated preparation answer to the user question. |
| verification_summary | string | Summarizes the overall judgment and the key evidence, or notes circumstances that prevent a determination. |
| overall_constraint_result | string | An overall judgment of whether the complete answer violates the explicit safety constraints supplied in the example. |
| overall_instruction_result | string | An overall judgment of whether the complete answer follows the applicable product-label instructions. |
| product_label_instructions | string | Original preparation instructions from the product label supplied in the example. |
| explicit_safety_constraints | string | Original explicit safety constraints supplied in the example. |
| has_explicit_constraint_violation | boolean | Indicates whether the complete answer contains a step that violates an explicit safety constraint. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

