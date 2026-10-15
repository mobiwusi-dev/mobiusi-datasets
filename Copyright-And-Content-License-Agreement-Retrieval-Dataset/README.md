---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Copyright and Content License Agreement Retrieval Dataset
---

# Copyright and Content License Agreement Retrieval Dataset

This dataset organizes original license terms and structured information for works, content libraries, images, music, film and television, and publishing content. It covers license types, granted rights, usage restrictions, attribution requirements, platform scope, and takedown conditions, with retrieval summaries and parsing confidence scores. It supports retrieval-augmented generation systems that need to locate usage boundaries, answer content rights questions, and assist with compliance review across digital media and publishing workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| license_type | string | The license type identified from the terms, such as exclusive, non-exclusive, free, commercial, or subscription-based. |
| rights_grants | array | Specific rights granted by the agreement and the scope in which they may be exercised. |
| work_metadata | object | Information about works, content, and rights holders extracted from the license text. |
| platform_scope | object | The license scope related to platforms, channels, devices, and audiences. |
| confidence_score | number | An overall confidence score for the structured parsing of license terms, ranging from 0 to 1. |
| raw_license_text | string | The original text of a copyright or content license agreement. |
| retrieval_summary | string | A summary for retrieval-augmented systems covering permitted uses, major restrictions, and key conditions. |
| usage_restrictions | object | Structured information about restrictions on commercial use, adaptation, sublicensing, redistribution, and public use. |
| takedown_conditions | object | Terms concerning infringement notices, breaches, license termination, and content takedown procedures. |
| attribution_requirements | array | Requirements for author credit, rights notices, source attribution, or links to the license. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

