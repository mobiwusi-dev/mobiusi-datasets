---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Passenger Railcar Product Technical Specification Extraction Benchmark
---

# Passenger Railcar Product Technical Specification Extraction Benchmark

Designed for passenger railcar manufacturing, this benchmark uses vehicle descriptions and technical specification text from manufacturer websites. It evaluates extraction of model names and versions, dimensions, passenger capacity, maximum speed, track gauge, and propulsion type, including the ability to retain values and units from the source text and associate attributes with the correct model or version. It supports the development, validation, and domain-specific comparison of product information extraction systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| width | string | The original value and unit for vehicle width, preserving ranges and approximate expressions. |
| height | string | The original value and unit for vehicle height, preserving ranges and approximate expressions. |
| length | string | The original value and unit for vehicle length, preserving ranges and approximate expressions. |
| model_name | string | The passenger railcar model name identified in the source text. |
| power_type | string | The propulsion type identified in the source text, such as battery electric, diesel, hybrid, or hydrogen fuel cell. |
| source_text | string | Original text from a passenger railcar manufacturer's website related to vehicle descriptions and technical specifications. |
| track_gauge | string | The original value and unit for track gauge, preserving ranges and approximate expressions. |
| maximum_speed | string | The original value and unit for maximum vehicle speed, preserving ranges and approximate expressions. |
| model_version | string | Version, configuration, or variant information identified in the source text; leave blank when not explicitly stated. |
| passenger_capacity | string | The original wording for passenger capacity or approved capacity, retaining ranges, seat counts, and other qualifications. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

