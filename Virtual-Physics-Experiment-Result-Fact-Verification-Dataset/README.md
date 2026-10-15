---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Virtual Physics Experiment Result Fact Verification Dataset
---

# Virtual Physics Experiment Result Fact Verification Dataset

This dataset covers virtual experiments in mechanics, electricity, optics, and thermodynamics, with structured JSON records of experiment setups, operation events, sensor readings, calculation steps, and result claims to be verified. Truth verdicts, confidence scores, and verification explanations support testing whether models can judge claims using experimental settings, physical laws, and simulation evidence. It is suitable for training, evaluating, and analyzing fact verification models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| confidence | number | The confidence score for the judgment, calculated from data completeness, error magnitude, and the degree of agreement with physical laws; values range from zero to one. |
| result_claim | object | The experiment result statement to be verified and its claimed value. |
| truth_verdict | boolean | A true or false judgment of the result claim based on physical laws, simulation readings, and error thresholds. |
| sensor_readings | array | Raw measurements collected by simulated sensors during the experiment. |
| experiment_setup | object | The virtual experiment domain, name, and initial parameters, provided as input for fact verification. |
| operation_events | array | User or system events recorded in chronological order during the virtual experiment. |
| calculation_process | object | Physical calculations and intermediate results derived from the experiment setup, operation events, and sensor readings. |
| verification_explanation | string | An explanation of why the result claim was judged true or false, identifying the key physical principles and reading evidence used. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

