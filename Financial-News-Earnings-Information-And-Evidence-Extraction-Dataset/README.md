---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Financial News Earnings Information and Evidence Extraction Dataset
---

# Financial News Earnings Information and Evidence Extraction Dataset

This dataset pairs original business and financial news articles with structured JSON annotations covering company names, ticker symbols, reporting periods, financial metrics, and year-over-year or quarter-over-quarter changes. Each extracted item is linked to an exact supporting passage with character offsets and a JSON-style field path, making the source of each result easy to verify. It supports structured-output supervised fine-tuning, financial information extraction, evidence grounding, and related model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| news_text | string | The original, unmodified business or financial news article used as the source for information extraction. |
| company_name | string | The company whose earnings or financial results are discussed in the article. |
| ticker_symbol | string | The company's stock ticker symbol as stated or unambiguously identified in the article. Omit this field when unavailable. |
| evidence_spans | array | Exact source-article spans supporting extracted fields, located with zero-based character offsets and an exclusive end offset, and associated with JSON-style field paths. |
| reporting_period | object | The fiscal or calendar period to which the reported financial results apply. |
| financial_metrics | array | Financial results and related changes reported for the company and reporting period, with one array item for each distinct metric. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

