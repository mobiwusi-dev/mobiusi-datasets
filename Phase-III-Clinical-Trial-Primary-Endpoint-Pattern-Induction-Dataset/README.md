---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Phase III Clinical Trial Primary Endpoint Pattern Induction Dataset
---

# Phase III Clinical Trial Primary Endpoint Pattern Induction Dataset

This dataset pairs evidence text from Phase III clinical trials across disease areas with questions that require comparison and induction. The source text covers study objectives, primary endpoints, and measurement time points; answers synthesize supported commonalities and differences while identifying evidence and inference limits. It is suited to clinical endpoint analysis, medical evidence synthesis, and reasoning-oriented supervised fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | A complete response to the induction question that combines supported commonalities and differences while avoiding claims beyond the source text. |
| evidence_basis | string | A concise explanation identifying which details in the supplied source text support the synthesis. |
| trial_evidence | string | Source text describing the relevant Phase III trials, including disease areas, study objectives, primary endpoints, and measurement time points. |
| inference_limits | string | A statement of uncertainties, missing information, and conclusions that cannot be drawn from the supplied evidence. |
| induction_question | string | A question asking for a comparison or pattern across the supplied trial evidence. |
| endpoint_differences | string | An evidence-based synthesis of differences in primary endpoint selection or definition, including relevant distinctions in disease, study objective, or measurement time point. |
| endpoint_commonalities | string | An evidence-based synthesis of shared features in primary endpoint selection or definition across the trials, when supported by the source text. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

