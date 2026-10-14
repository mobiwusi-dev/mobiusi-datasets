---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Social Media Influencer Recommendation Fact Verification Dataset
---

# Social Media Influencer Recommendation Fact Verification Dataset

This dataset features synthetic recommendation copy modeled on social media influencer reviews, user testimonials, and native ads, paired with evidence that supports or challenges related claims. It covers personal experiences, objective product attributes, and generalized conclusions, with structured annotations for claim units, evidence support, and improper generalization. It supports fact verification training, advertising content review, and recommendation copy risk assessment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_units | array | Verifiable claims extracted from the recommendation copy, including their subject scope, category, and corresponding evidence references. |
| analysis_rationale | string | Explains the basis for the judgment by describing the relationships among personal experience, product attributes, generalized conclusions, and supporting evidence. |
| verification_label | string | The final classification of the recommendation copy's factual risk and any extension of personal experience. |
| recommendation_text | string | Complete recommendation copy from an influencer review, user testimonial, or native ad. |
| supporting_evidence | string | Evidence text used to support or challenge claims about effects, experiences, product attributes, or generalized conclusions. |
| evidence_support_level | string | Assesses how completely and adequately the supporting evidence covers the recommendation claims. |
| improper_generalization | boolean | Indicates whether personal experience or limited evidence is extended into a general fact without sufficient support. |
| generalization_direction | string | Describes the scope from which a claim is generalized and the scope to which it is extended. |
| product_attribute_mentions | array | Product features, ingredients, performance, or other objective attributes identified in the recommendation copy. |
| personal_experience_present | boolean | Indicates whether the copy describes a publisher's or specific user's experience, impressions, or results from using the product. |
| generalized_conclusion_present | boolean | Indicates whether the copy presents an individual or limited observation as a general conclusion applicable to most or all people. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

