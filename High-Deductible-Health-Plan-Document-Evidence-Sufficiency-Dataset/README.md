---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: High-Deductible Health Plan Document Evidence Sufficiency Dataset
---

# High-Deductible Health Plan Document Evidence Sufficiency Dataset

This dataset organizes claims and supporting text evidence from high-deductible health plan documents, benefit explanations, and related legal documents. Topics include deductibles, cost sharing, covered services, and exclusions, with annotations indicating whether evidence supports or contradicts a claim, whether it is sufficient to reach a judgment, and what plan, service, or time period it applies to. Use it to train and evaluate health plan provision verifiers for evidence assessment, scope recognition, and rationale generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The claim about a plan term, such as a deductible, cost-sharing requirement, covered service, or exclusion. |
| document_context | string | Relevant surrounding text or source context from the plan document, benefits explanation, or related legal document. |
| evidence_excerpt | string | The verbatim or faithfully transcribed passage offered as evidence for or against the claim. |
| evidence_relation | string | The assessed relationship between the cited evidence and the claim. |
| applicability_scope | string | A concise description of relevant scope conditions, such as plan option, coverage tier, effective period, service type, or participant eligibility. |
| assessment_rationale | string | A concise explanation citing how the evidence supports, contradicts, or fails to resolve the claim and any relevant applicability limitations. |
| sufficiency_judgment | string | The annotation indicating whether the evidence sufficiently supports the claim, sufficiently contradicts it, or is insufficient to determine the claim. |
| applicability_judgment | string | Whether the evidence applies to the plan, person, service, time period, or other scope stated in the claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

