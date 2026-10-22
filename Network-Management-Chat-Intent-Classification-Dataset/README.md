---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Network Management Chat Intent Classification Dataset
---

# Network Management Chat Intent Classification Dataset

This dataset contains chat requests from administrators and operations staff working with network and systems management software, covering network devices, services, and infrastructure. Each request is labeled with a primary intent category, a more specific intent subcategory, and a concise intent summary; common needs include monitoring, configuration, troubleshooting, access management, and information retrieval. It supports training and evaluating models for operations request understanding, intent routing, and task-specific fine-tuning of network management assistants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| chat_request | string | The original request from an administrator or operations staff member about a network device, service, or infrastructure. |
| intent_summary | string | A concise summary of the primary operation or information need expressed in the request. |
| intent_category | string | The broad intent identified in the request, such as monitoring, configuration, troubleshooting, access management, or information retrieval. |
| intent_subcategory | string | The specific action or information need expressed in the request, such as checking device status, restarting a service, or updating a firewall rule. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

