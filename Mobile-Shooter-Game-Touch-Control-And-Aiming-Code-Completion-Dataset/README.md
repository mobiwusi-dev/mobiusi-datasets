---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mobile Shooter Game Touch Control and Aiming Code Completion Dataset
---

# Mobile Shooter Game Touch Control and Aiming Code Completion Dataset

Focused on mobile shooter game development, this dataset contains code completion samples for touch-based movement, camera control, aiming input, fire-button interactions, and input-state coordination. Each sample pairs a code context with the expected completion, targeting game-specific touch and aiming logic. It supports code supervised fine-tuning, game development assistance, and evaluation of code completion for gameplay controls.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| code_context | string | The source-code context, including the incomplete section to be completed. |
| control_topics | array | Derived labels identifying the touch-control and aiming concepts covered by the completion. |
| completion_prompt | string | A model-ready prompt derived from the code context and requesting completion of the missing logic. |
| expected_completion | string | The reference code that fills in the incomplete section of the context. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

