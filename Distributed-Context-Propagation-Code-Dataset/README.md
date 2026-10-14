---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Distributed Context Propagation Code Dataset
---

# Distributed Context Propagation Code Dataset

This dataset collects source code implementations for handling request contexts, trace identifiers, and cross-service metadata across multiple programming languages and frameworks. It covers common service boundaries, including HTTP, RPC, messaging, and service mesh integrations, with structured annotations for languages, frameworks, context APIs, metadata carriers, and propagation stages. It supports coding agent training and evaluation, distributed tracing analysis, and code understanding and generation for microservice context propagation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| framework | string | The primary application framework, RPC framework, service mesh component, or client library identified in the source code. |
| code_summary | string | An English summary of the context creation, extraction, injection, forwarding, and restoration logic in the source code. |
| source_artifact | object | The source code to be analyzed and its original file metadata. |
| context_api_names | array | Names of APIs, classes, functions, or methods used to create, read, modify, or pass request context in the code. |
| metadata_carriers | array | Carriers used to propagate context metadata across threads, processes, or services, such as request headers, RPC metadata, message attributes, or environment variables. |
| propagation_stages | array | Context propagation stages represented in the code, such as inbound extraction, context injection, client calls, or server-side restoration. |
| propagation_pattern | string | The context propagation pattern inferred from the code, such as explicit parameter passing, implicit thread context, header injection, or automatic service mesh injection. |
| programming_language | string | The primary programming language identified in the source code. |
| service_boundary_types | array | Types of service boundaries crossed by the code, such as HTTP, gRPC, message queues, database calls, or service mesh proxies. |
| trace_identifier_types | array | Types of trace identifiers propagated or extracted in the code, such as trace_id, span_id, or request correlation identifiers. |
| supports_cross_service_propagation | boolean | Whether the source code can propagate request context, trace identifiers, or related metadata to other services. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

