---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Psychotherapy Case Formulation Evidence Grounding and Faithfulness Evaluation Dataset
---

# Psychotherapy Case Formulation Evidence Grounding and Faithfulness Evaluation Dataset

This dataset contains psychotherapy session transcripts, model-generated case formulations, and claim-level annotations for interpretations, pattern summaries, and hypotheses, including the related dialogue evidence and its degree of support. It evaluates whether models accurately ground formulation claims in session content and distinguish explicit statements from inferences. The data supports faithfulness evaluation, evidence-grounding analysis, and domain-specific model assessment in psychotherapy.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_annotations | array | Annotations for individual interpretations, patterns, or hypotheses in the model-generated formulation, including supporting dialogue evidence and its degree of support. |
| model_formulation | string | The model-generated case formulation to be evaluated. |
| session_transcript | string | The source text of the psychotherapy session, including speaker labels or turn markers when available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

