---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mining Drill Trajectory Calculation Q&A Dataset
---

# Mining Drill Trajectory Calculation Q&A Dataset

This dataset contains question-and-answer examples for calculating mining drill trajectories. Inputs include collar easting, northing, elevation, azimuth, inclination, and drilled depth; outputs include bottom coordinates, horizontal displacement, and deviation from a vertical trajectory. Examples call for step-by-step calculations with units and use explicit conventions for azimuth and inclination, supporting model training and evaluation in coordinate reasoning and trajectory calculation for mining drilling robots.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| azimuth_deg | number | Hole azimuth in degrees, measured clockwise from north; valid values range from 0 to 360. |
| final_answer | string | Concise answer reporting the calculated bottom coordinates, horizontal displacement, and trajectory deviation with units. |
| drill_depth_m | number | Measured distance drilled along the hole from the collar, in meters; must be non-negative. |
| question_text | string | The original user question containing the drillhole information and calculation request. |
| inclination_deg | number | Downward hole inclination in degrees measured from horizontal, where 0 is horizontal and 90 is vertically downward. |
| bottom_easting_m | number | Calculated easting coordinate at the bottom of the hole, in meters. |
| collar_easting_m | number | Easting coordinate of the hole collar, in meters, extracted from the question. |
| bottom_northing_m | number | Calculated northing coordinate at the bottom of the hole, in meters. |
| calculation_steps | string | Step-by-step derivation with formulas, substituted values, units, and intermediate results. Use horizontal displacement = depth × cos(inclination), easting offset = horizontal displacement × sin(azimuth), northing offset = horizontal displacement × cos(azimuth), and elevation change = −depth × sin(inclination). |
| collar_northing_m | number | Northing coordinate of the hole collar, in meters, extracted from the question. |
| bottom_elevation_m | number | Calculated elevation coordinate at the bottom of the hole, in meters. |
| collar_elevation_m | number | Elevation of the hole collar, in meters, extracted from the question; elevation is positive upward. |
| trajectory_deviation_deg | number | Calculated angular deviation from a vertically downward trajectory, in degrees, defined as 90 degrees minus the downward inclination. |
| horizontal_displacement_m | number | Calculated horizontal distance from the collar to the hole bottom, in meters. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

