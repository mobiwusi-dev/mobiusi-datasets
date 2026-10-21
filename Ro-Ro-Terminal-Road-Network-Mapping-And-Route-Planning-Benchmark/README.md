---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Ro-Ro Terminal Road Network Mapping and Route Planning Benchmark
---

# Ro-Ro Terminal Road Network Mapping and Route Planning Benchmark

Designed for Ro-Ro terminal operations, this benchmark covers internal roads, vehicle staging areas, gates, loading berths, road connectivity, and access restrictions, together with vehicle routing requests. It supports evaluation of models that transform structured road network data into spatial graphs and plan feasible routes for vehicle entry, staging, and movement to loading berths. Typical applications include intelligent navigation, operational dispatch, and spatial reasoning evaluation for Ro-Ro transport.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| network_links | array | Derived directed or undirected connections between network nodes, including measurable attributes and access restrictions. |
| network_nodes | array | Derived graph nodes representing operational locations and road junctions within the terminal. |
| route_results | array | Derived route plans for requested vehicle movements, including ordered paths, cost estimates, and feasibility outcomes. |
| network_source | object | Original structured source data describing terminal roads, vehicle staging areas, gates, berths, and traffic restrictions. |
| routing_request_source | object | Original structured input describing vehicle routing requests, including requested origins, destinations, and vehicle requirements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

