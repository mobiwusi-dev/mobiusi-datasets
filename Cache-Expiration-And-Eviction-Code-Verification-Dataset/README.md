---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cache Expiration and Eviction Code Verification Dataset
---

# Cache Expiration and Eviction Code Verification Dataset

This dataset contains source code examples involving TTL settings, expiration checks, capacity limits, and eviction strategy interactions in distributed caches. Annotations assess whether implementations handle boundary conditions and cache entry lifecycles correctly, and analyze common defect root causes and potential risks in distributed environments. It supports training and evaluating code verification, debugging, and root-cause analysis models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_correct | boolean | Indicates whether the code correctly handles TTL, expiration boundaries, eviction strategies, and entry lifecycles. |
| source_code | string | Cache expiration and eviction implementation code to be verified. |
| defect_root_cause | string | Describes common implementation defect causes, or states that no obvious defect was found. |
| eviction_analysis | object | Explains cache capacity limits, eviction triggers, and the strategy used to select entries for eviction. |
| boundary_case_results | array | Validation results for boundary cases involving TTL, expiration checks, capacity limits, and concurrent interactions. |
| ttl_expiration_analysis | object | Analysis of TTL configuration, expiration criteria, and expiration-check logic. |
| entry_lifecycle_analysis | object | Analyzes cache entry state changes and cleanup behavior from insertion through expiration, eviction, or deletion. |
| distributed_cache_risk_analysis | object | Analyzes potential risks involving expiration and eviction when the code runs in a distributed environment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

