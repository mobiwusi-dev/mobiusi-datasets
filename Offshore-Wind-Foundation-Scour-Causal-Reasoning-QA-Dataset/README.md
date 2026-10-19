---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Offshore Wind Foundation Scour Causal Reasoning QA Dataset
---

# Offshore Wind Foundation Scour Causal Reasoning QA Dataset

Focused on monopile and jacket foundations for fixed-bottom offshore wind turbines, this dataset covers scour, seabed conditions, local flow changes, and foundation response. Questions and explanatory answers describe how hydrodynamic and seabed conditions can initiate or alter scour near a foundation, and how scour may affect soil support and structural stability. The data supports training and evaluation of engineering causal reasoning, including the distinction between observed correlations and well-supported causal mechanisms.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The explanatory answer describing relevant observations and reasoning about scour and foundation response. |
| question | string | The source question about scour, seabed conditions, local flow changes, or foundation response. |
| causal_chain | array | An ordered sequence of concise statements linking environmental conditions, scour, soil support, and foundation response. |
| foundation_type | string | The foundation type identified or normalized from the question and answer, such as monopile, jacket, or unspecified. |
| causal_mechanism | string | The physical mechanism explaining how local flow and seabed conditions produce or modify scour near the foundation. |
| scour_description | string | A concise description of the scour process or seabed erosion discussed in the record. |
| soil_support_effect | string | The inferred effect of scour on surrounding soil support, including changes in embedment, stiffness, or resistance where applicable. |
| structural_stability_effect | string | The inferred consequence of altered soil support for foundation response or structural stability. |
| correlation_causation_distinction | string | An explanation distinguishing observed associations from supported causal mechanisms, including any stated uncertainty or alternative explanation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

