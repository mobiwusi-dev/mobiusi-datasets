---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mine Dewatering Pump Group Operating Condition Calculation Verification Dataset
---

# Mine Dewatering Pump Group Operating Condition Calculation Verification Dataset

This structured JSON dataset records mine dewatering system conditions, pipeline parameters, pump performance curves and group configurations, along with candidate calculations to verify and their reference calculation basis. It covers key measures including static head, pipeline losses, total head, operating flow, pump group head, efficiency, and power, supporting checks of calculation errors against permitted tolerances. It is intended for training and evaluating calculation outcome verifiers for mine dewatering equipment, as well as testing professional calculation workflows and quality control.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| validation_results | object | Errors and pass status obtained by comparing candidate calculation results with reference values using the permitted relative error. |
| drainage_conditions | object | Original operating parameters used to calculate the dewatering system static head and hydraulic power. |
| pipeline_parameters | object | Original dimensions and resistance parameters for the suction and discharge pipes, used to estimate pipeline losses. |
| pump_performance_data | object | Records sampled performance curve points for an individual pump and the number of pumps connected in series or parallel. |
| calculated_total_head_m | number | Total head required by the pump group, calculated by combining the static head and pipeline losses at the operating flow, in meters. |
| calculated_static_head_m | number | Static head calculated from the discharge outlet elevation, sump water level elevation, and outlet pressure head, in meters. |
| calculated_pipeline_loss_m | number | Combined friction and local head losses calculated from pipeline length, diameter, and resistance parameters at the calculated operating flow, in meters. |
| candidate_operating_results | object | Pump group operating conditions and power values submitted for comparison with reference calculations. |
| reference_calculation_basis | object | Records the calculation notes, permitted tolerances, and reference identifiers used to verify results. |
| calculated_pump_group_head_m | number | Operating head calculated from the number of pumps in series and the individual pump performance curve, in meters. |
| calculated_efficiency_percent | number | Pump group operating efficiency derived from the individual pump performance curve at the operating point, as a percentage. |
| calculated_hydraulic_power_kw | number | Hydraulic power calculated from water density, gravitational acceleration, operating flow, and total head, in kilowatts. |
| calculated_operating_flow_m3_h | number | Pump group operating flow calculated at the intersection of the system curve and pump performance curve, in cubic meters per hour. |
| calculated_group_shaft_power_kw | number | Total pump group shaft power derived from the calculated hydraulic power and operating efficiency, in kilowatts. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

