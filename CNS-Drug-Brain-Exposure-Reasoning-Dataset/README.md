---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: CNS Drug Brain Exposure Reasoning Dataset
---

# CNS Drug Brain Exposure Reasoning Dataset

This question-answer dataset focuses on comparing brain exposure among candidate small molecules for central nervous system drug discovery. Samples provide information such as physicochemical properties, transporter data, plasma and brain tissue exposure, and unbound drug fractions, and require analysis of likely brain exposure, distribution-limiting factors, and the distinction between measured evidence and predictions or inferences. It supports reasoning supervised fine-tuning, drug development question answering, and evidence-provenance evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_text | string | Original question and supplied candidate-drug information, including physicochemical properties, transporter data, plasma and brain exposure, and unbound fractions. |
| limiting_factors | string | Identify and explain factors that may constrain brain distribution, such as physicochemical properties, transporter effects, or unbound drug fraction. |
| reasoning_answer | string | Provide a concise, integrated answer that explains the comparison using the supplied evidence and avoids unsupported conclusions. |
| evidence_provenance | string | Distinguish directly measured evidence from predicted or inferred information, noting uncertainty where appropriate. |
| exposure_comparison | string | Compare the candidates' likely brain exposure and state the conclusion supported by the supplied evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

