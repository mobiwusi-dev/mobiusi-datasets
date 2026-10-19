---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Microscopy Facility Access and Use Policy Fact Extraction Dataset
---

# Microscopy Facility Access and Use Policy Fact Extraction Dataset

This dataset focuses on user access, reservations, fees, and equipment-use policies published on public core microscopy and imaging facility webpages. It pairs source webpage content with structured facts covering eligibility, reservation rules, fee conditions, equipment restrictions, access limits, and effective dates. It supports policy extraction, structured-output training, and retrieval of facility operating rules.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| fee_rules | array | Rates, billing conditions, waivers, and other charges associated with facility access or services. |
| source_url | string | The URL of the webpage containing the facility policies. |
| access_limits | array | Additional limits on facility access, including location, hours, conduct, and user-specific restrictions. |
| facility_name | string | The name of the microscopy facility or platform identified in the source. |
| effective_date | string | The effective date or date range of the extracted policies, if stated. |
| eligibility_rules | array | Eligibility criteria and required qualifications for users or user groups. |
| reservation_rules | array | Rules governing appointment requests, booking windows, cancellations, and scheduling limits. |
| equipment_use_rules | array | Instrument-specific requirements, permitted-use conditions, and operating restrictions. |
| source_page_content | string | The original webpage content used as the source for policy extraction. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

