---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: High-Definition Map Cross-Layer Spatial Consistency Benchmark
---

# High-Definition Map Cross-Layer Spatial Consistency Benchmark

Designed for evaluating urban road HD maps, this benchmark covers GIS layers such as lane markings, lane centerlines, road boundaries, and road facilities, together with feature geometries and coordinate reference information. It provides spatial relation queries and reference judgments for positions, alignment errors, and containment across layers or features, enabling assessment of a model's understanding of spatial relationships in multilayer HD maps. Typical applications include 2D spatial understanding evaluation, map data quality checks, and related model development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| gis_layer_data | object | Raw GIS data for layers such as lane markings, lane centerlines, road boundaries, and road facilities, including features, geometric coordinates, and coordinate reference information. |
| relation_query | string | Describes the two layers or features being evaluated and the spatial relation to determine. |
| relation_exists | boolean | Indicates whether the spatial relation stated in the query holds. |
| alignment_error_m | number | The alignment error in meters, calculated from the geometric positions of the relevant layers or features. |
| containment_status | string | Records the containment judgment between target features; not applicable indicates that the query does not involve containment. |
| reference_relation | string | The spatial relation category established from layer geometries and reference annotations. |
| reference_explanation | string | Explains the geometric position, boundary alignment, or containment evidence supporting the reference spatial relation judgment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

