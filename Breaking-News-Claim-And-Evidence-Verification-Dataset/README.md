---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Breaking News Claim and Evidence Verification Dataset
---

# Breaking News Claim and Evidence Verification Dataset

Designed for fact-checking breaking news webpages, this dataset pairs verifiable factual claims with source webpage information, relevant evidence spans, verdicts, and supporting rationales. Labels can indicate that evidence supports or contradicts a claim, or that the available evidence is insufficient. It supports evidence retrieval, claim-evidence matching, evidence-based judgment, and the development and evaluation of newsroom fact-checking workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | The conclusion reached about the claim after considering the webpage evidence. |
| claim_text | string | A verifiable factual claim that must be checked against webpage evidence. |
| evidence_spans | array | Evidence excerpts extracted from webpage content and their relationship to the claim. |
| source_webpage | object | The original webpage used as verification evidence, along with its source information. |
| verdict_rationale | string | An explanation of how the evidence supports the verdict and what information remains missing when evidence is insufficient. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

