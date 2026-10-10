---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Luxury Hotel Dining Catalog Attribute Extraction Dataset
---

# Luxury Hotel Dining Catalog Attribute Extraction Dataset

This dataset contains natural-language descriptions of luxury hotel restaurants, bars, and dining experiences, organized into structured attributes such as venue name, venue type, service periods, service formats, cuisines, and dietary restrictions or accommodations. Its catalog coverage includes information such as breakfast, lunch, dinner, and all-day service, as well as dine-in, room service, buffet, and afternoon tea; the actual records depend on the dataset contents. It is suitable for structured-output supervised fine-tuning, dining catalog organization, hotel product information retrieval, and attribute extraction evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| cuisines | array | Cuisines or primary culinary styles mentioned in the description. |
| venue_name | string | Name of the restaurant, bar, or dining experience extracted from the source description. |
| venue_type | string | Primary category of the dining catalog entry, such as a restaurant, bar, or dining experience. |
| service_formats | array | Dining service formats, such as dine-in, room service, buffet, or afternoon tea. |
| service_periods | array | Periods when the venue or experience provides service, such as breakfast, lunch, dinner, or all-day service. |
| source_description | string | Natural-language description of a dining venue or experience, provided as the input for attribute extraction. |
| dietary_restrictions | array | Dietary restrictions or accommodations mentioned in the description, such as vegetarian, vegan, gluten-free, or halal options. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

