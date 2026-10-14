---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Timeliness and Availability Fact Verification Dataset for Advertising Claims
---

# Timeliness and Availability Fact Verification Dataset for Advertising Claims

This dataset focuses on social media advertising claims about product launches, service coverage, delivery times, inventory, promotion deadlines, and newly available features. It provides synthetic ad text alongside temporal, geographic, and availability constraints, supporting evidence, and structured validation results. Use it to train and evaluate models that detect outdated claims, geographic mismatches, unavailable offerings, and claims lacking current evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The social media advertising claim or synthetic ad text to be verified. |
| risk_flags | array | One or more advertising claim risk types identified from the validation results. |
| evidence_text | string | Text used to support, refute, or assess the timeliness and availability of the advertising claim. |
| claim_analysis | object | The topic, subject, and time- or location-dependent attributes extracted from the advertising claim. |
| confidence_score | number | The confidence assigned by the model or annotation process to the final validation label, on a scale from 0 to 1. |
| validation_label | string | The overall label determined from the temporal, geographic, availability, and evidence validation results. |
| constraint_context | object | Time, location, service-area, and availability context used to assess whether the advertising claim is valid. |
| evidence_validation | object | An assessment of how well the evidence supports the advertising claim and whether it is timely and relevant. |
| temporal_validation | object | The result of comparing the claim's time conditions with the reference time. |
| geographic_validation | object | The result of comparing the location scope in the advertising claim with the actual service or coverage area. |
| availability_validation | object | The result of comparing the stated inventory, service, or feature availability with the contextual records. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

