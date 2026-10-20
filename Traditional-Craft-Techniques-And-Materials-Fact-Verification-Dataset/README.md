---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Traditional Craft Techniques and Materials Fact Verification Dataset
---

# Traditional Craft Techniques and Materials Fact Verification Dataset

This dataset organizes verification examples about traditional craft techniques, material use, and craft characteristics through structured claims and traceable domain knowledge records. It provides verdicts, rationales, confidence scores, and alignments between claim elements and supporting knowledge, including supported, refuted, and insufficient-evidence outcomes. The data focuses on metadata rather than full-text or image evidence, making it suitable for training and evaluating craft knowledge verification and grounding capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim | object | The original traditional craft factual claim and its structured elements, provided as input. |
| knowledge_record | object | A structured craft knowledge record with traceable source metadata, provided as input; it does not contain full-text or image evidence. |
| evidence_alignment | array | Lists the structured correspondences between claim elements and the domain knowledge record used for verification. |
| verification_result | string | The fact verification label derived from the claim and the structured domain knowledge record. |
| verification_rationale | string | Explains how the knowledge record supports or refutes the claim, or why the available basis is insufficient. |
| verification_confidence | number | An estimate of the reliability of the verification result, ranging from 0 to 1. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

