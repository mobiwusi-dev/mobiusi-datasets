---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Terraform Network Segmentation Reachability Reasoning Dataset
---

# Terraform Network Segmentation Reachability Reasoning Dataset

This dataset includes Terraform and other infrastructure-as-code configurations for cloud networks, security groups, network ACLs, routes, and their references, paired with supervised questions about reachability between specified resources. Examples cover reachability decisions, identification of applicable rules, and explanations of the results, helping models understand cross-resource references and network rule semantics. It is designed for supervised fine-tuning and evaluation of models for network segmentation analysis, code understanding, and reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | A concise explanation of how resource references and network rule semantics determine the reachability result. |
| effective_rules | array | The security group, network ACL, and route rules that determine the reachability result. |
| reachability_result | boolean | Indicates whether the queried source and destination resources can reach each other under the configured rules. |
| referenced_resources | array | Terraform resources and cross-resource references relevant to the reachability question. |
| reachability_question | string | A question about whether specified resources can communicate and which network rules apply. |
| terraform_source_code | string | Terraform configuration code containing network, security group, network ACL, and route resources, along with their references. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

