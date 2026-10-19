---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Domestic Arbitration Disputed Facts and Evidence Sufficiency Dataset
---

# Domestic Arbitration Disputed Facts and Evidence Sufficiency Dataset

This dataset contains disputed factual claims drawn from domestic arbitration requests, statements of defense, related legal documents, and supporting evidence, with structured annotations linking claims to the evidence offered in support. Annotations cover the claiming party, the opposing position, fact type, evidence sufficiency status, rationale, key evidence gaps, conflicts, and reasons an assessment cannot be made. It supports training and evaluating legal document verifiers for claim verification, evidence analysis, and assessment-boundary recognition.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| key_gaps | array | Important missing materials, matters requiring verification, or gaps in the chain of proof that affect fact finding; recorded as an empty array when no clear gap is identified. |
| fact_type | string | The primary category of fact addressed by the disputed claim. |
| claim_text | string | A specific factual claim extracted from the source materials that requires assessment of its evidentiary support. |
| claimant_party | string | The party that advances the disputed factual claim; recorded as undetermined when the materials do not identify the party. |
| evidence_items | array | Evidence relevant to the factual claim, including its content, relevance, and limitations. |
| support_reason | string | The specific reasons for the evidence sufficiency assessment, based on the claim and the related evidence. |
| support_status | string | The assessment of how the available materials support the specific factual claim. |
| conflict_details | string | A description of conflicting evidence, the point of conflict, and its effect on the factual assessment; recorded as none when no conflict exists. |
| respondent_position | string | The opposing party's admission, denial, dispute, or other response to the factual claim; recorded as not mentioned when the materials do not address it. |
| unassessable_reason | string | The reason an assessment cannot be made, such as missing key materials, incomplete text, or an unclear claim; recorded as not applicable when this does not apply. |
| source_document_text | string | Original or text-extracted content from arbitration requests, statements of defense, related legal documents, and evidence materials used as the source for this annotation. |
| assessment_confidence | number | Confidence in the evidence sufficiency assessment, expressed as a value from 0 to 1. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

