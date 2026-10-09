---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Transportation Metrics and Statistical Claim Verification Dataset
---

# Transportation Metrics and Statistical Claim Verification Dataset

This dataset contains statistical claims from web-based transportation planning reports, covering metrics such as passenger volumes, modal shares, travel times, and vehicle miles traveled. Records preserve verification context, including metric definitions, values, units, reference periods, and geographic scope, alongside source text, evidence excerpts, verification labels, and rationales. It supports fact-verification model training and evaluation, as well as transportation statistics extraction and evidence analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| unit | string | The unit or scale associated with the statistical value, such as passenger trips, percent, minutes, or kilometers. |
| claim_text | string | The complete statistical statement extracted from the source text for fact verification. |
| metric_name | string | The transportation metric addressed by the claim, such as passenger volume, modal share, travel time, or vehicle miles traveled. |
| source_text | string | Original text from a transportation planning report webpage, provided as the basis for claim extraction and verification. |
| evidence_quote | string | A passage from the source text that supports, contradicts, or is used to assess the statistical claim. |
| transport_mode | string | The transport mode addressed by the claim, such as bus, rail transit, private car, walking, or cycling; may be left blank when not applicable. |
| statistic_value | number | The numeric value in the claim. Values such as percentages are recorded numerically; the corresponding unit is provided separately. |
| geographic_scope | string | The city, region, administrative area, or other spatial scope addressed by the claim. |
| reference_period | string | The year, range of years, or other time period covered by the statistic. |
| metric_definition | string | The metric's stated scope, statistical subject, or calculation definition from the source; may be left blank if not provided. |
| verification_label | string | The assessment of the relationship between the source evidence and the statistical claim. |
| verification_rationale | string | An explanation of why the source evidence supports, contradicts, or is insufficient to assess the claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

