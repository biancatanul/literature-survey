# Lavalle2020: An Approach to Automatically Detect and Visualize Bias in Data Analytics

- **Type:** workshop paper
- **Priority:** primary
- **Reference:** see `references.bib`, key `Lavalle2020`

## Summary

Bias detection and visualization aimed at non-expert users. The detection algorithm looks at every column that seems categorical (fewer distinct values than 5% of the rows) and compares its most and least frequent values with the score (max - min) / max * 10. A column is flagged as biased if the score exceeds a user-adjustable threshold (default 8).

Here, bias means class imbalance and dataset shift. The paper does not mention sensitive attributes such as gender or ethnicity, has no fairness metrics, and does not look at labels or outcomes. In short, it detects imbalance without focusing on fairness.

## Use in my thesis

Closest existing work to my application (automatic detection plus visualization for non-experts). Starting point for the related work chapter and for the gap statement.

## Gap

No sensitive attributes, no outcome or label analysis, no fairness metrics.

## Related notes

Extended version: [Lavalle2023](Lavalle2023.md) (full methodology, metamodel, case study).
