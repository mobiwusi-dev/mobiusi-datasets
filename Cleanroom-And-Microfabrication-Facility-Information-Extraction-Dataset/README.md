---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cleanroom and Microfabrication Facility Information Extraction Dataset
---

# Cleanroom and Microfabrication Facility Information Extraction Dataset

This dataset uses official websites and facility pages for cleanrooms and microfabrication platforms as input, capturing details such as facility names and types, cleanroom classifications, environmental conditions, services, user groups, equipment, and locations. Its structured fields include source evidence, supporting model training to identify facility information in webpage text and produce consistent outputs. It is suitable for cleanroom facility search, resource catalog development, and training or evaluating information extraction models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| location | object | The facility's institutional and geographic location, using only details available in the source. |
| facility_name | string | The official name of the cleanroom, facility, or platform. |
| platform_type | string | The type of facility or platform, such as a cleanroom, nanofabrication center, or microfabrication laboratory. |
| service_users | array | User groups or organizations served by the facility, such as academic researchers, companies, or students. |
| source_content | string | The original HTML content of the facility webpage used as the extraction input. |
| source_evidence | array | Brief quotations or close paraphrases from the webpage that support the extracted facility profile. |
| available_services | array | Services, processes, or capabilities offered to facility users. |
| available_equipment | array | Key equipment or tool types explicitly mentioned as available at the facility. |
| environmental_conditions | array | Environmental parameters and operating conditions reported for the facility, such as temperature, humidity, or pressure. |
| cleanroom_classifications | array | Cleanliness standards and classifications stated for the facility, including standard names and class levels when available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

