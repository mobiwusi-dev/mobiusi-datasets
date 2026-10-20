---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Temperature Sensor Product Specification Information Extraction Benchmark
---

# Temperature Sensor Product Specification Information Extraction Benchmark

This benchmark uses text from temperature sensor manufacturers' product pages and online technical catalogs as input, with structured reference answers for attributes such as sensing range, accuracy, output type, response time, and mounting method. It supports evaluation of a model's ability to identify and extract specifications from web text, as well as benchmarking, system comparisons, and iterative improvement of information extraction solutions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| accuracy | string | The stated measurement accuracy or tolerance, preserving the values and units provided in the source. |
| output_type | string | The sensor's output signal type or output interface format. |
| source_text | string | Temperature sensor text from a manufacturer product page or online technical catalog. |
| response_time | string | The response time stated for the product, preserving the values and units provided in the source. |
| sensing_range | string | The temperature range measurable by the sensor, preserving the values and units stated in the source. |
| mounting_method | string | The mounting method supported or required by the product. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

