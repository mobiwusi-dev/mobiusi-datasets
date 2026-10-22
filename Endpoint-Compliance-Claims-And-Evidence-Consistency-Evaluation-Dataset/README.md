---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Endpoint Compliance Claims and Evidence Consistency Evaluation Dataset
---

# Endpoint Compliance Claims and Evidence Consistency Evaluation Dataset

This benchmark dataset contains JSON records of endpoint compliance claims alongside related configuration check results, telemetry observations, and audit evidence. It evaluates whether the available evidence supports each claim, including cases with missing or incomplete evidence and conflicts across sources. Designed for evidence-based verification rather than classification of claim fields alone, it supports automated consistency evaluation in endpoint management, digital workplace, and security compliance workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| audit_evidence | object | Available audit records relevant to the compliance claim; this source may be absent or incomplete. |
| contradictions | array | Conflicts among the claim, configuration checks, telemetry observations, and audit records. |
| claim_supported | boolean | Whether the available evidence positively supports the compliance claim. |
| compliance_claim | object | The original endpoint compliance conclusion and its identifying context. |
| missing_evidence | array | Evidence items or source details needed for verification that are absent from the input record. |
| assessment_status | string | An evidence-based assessment of whether the available inputs support the claimed compliance status. |
| telemetry_evidence | object | Available endpoint telemetry observations used as evidence; the object or its observations may be absent. |
| assessment_rationale | string | A concise explanation connecting the available evidence, evidence gaps, or contradictions to the assessment status. |
| conclusion_alignment | string | How the available evidence aligns with the stated compliance conclusion. |
| configuration_checks | array | Available configuration check results. This source may be absent or incomplete when evidence is missing. |
| evidence_completeness | string | The assessed completeness of the evidence needed to verify the claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

