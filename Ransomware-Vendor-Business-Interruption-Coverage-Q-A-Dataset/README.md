---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Ransomware Vendor Business Interruption Coverage Q&A Dataset
---

# Ransomware Vendor Business Interruption Coverage Q&A Dataset

This dataset focuses on insurance questions about business interruption losses incurred by an insured after a third-party vendor is hit by ransomware. It covers vendor relationships, service dependencies, interruption facts, and relevant policy terms. The questions require models to connect incident causes, business impacts, and coverage conditions to assess whether coverage applies and what limitations may affect it, supporting multi-hop reasoning training and evaluation in insurance contexts.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The direct answer to the coverage question, grounded in the case facts and policy terms. |
| question | string | The coverage question extracted from or formulated using the source material. |
| coverage_status | string | The overall coverage assessment based on the available facts and policy conditions. |
| source_material | string | Original case facts and policy information, including the vendor relationship, service dependency, interruption facts, and relevant policy terms. |
| reasoning_explanation | string | A multi-step explanation connecting the vendor's ransomware incident, the insured's service dependency and business interruption, and the applicable coverage conditions. |
| applicable_limits_and_exclusions | string | Relevant sublimits, waiting periods, exclusions, or other policy restrictions affecting the coverage assessment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

