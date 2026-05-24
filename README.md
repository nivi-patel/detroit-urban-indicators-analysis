# Detroit Urban Indicators: Comparative Census Analysis

Comparative statistical analysis of Detroit against 2,600+ US urban 
areas across three Census-derived indicators: housing vacancy, 
car dependency, and poverty rates.

## Research Questions
- How does Detroit compare to other urban areas on vacancy, 
  transit, and poverty indicators?
- What census variables best predict poverty levels across US cities?

## Methods
- Data normalization (per 1,000 residents) for cross-city comparability
- Descriptive statistics: mean, median, standard deviation
- Z-score analysis to position Detroit relative to national urban distribution
- 95% Confidence intervals for all three indicators
- One-way ANOVA testing transit mode differences across poverty levels 
  (F = 170.2, p < 2e-16)
- Tukey HSD post-hoc test for pairwise poverty group comparisons
- Multivariate regression: poverty ~ education + employment + race 
  (Adjusted R² = 0.416)

## Key Findings
- Detroit's housing vacancy (39.3/1000) is significantly below the 
  urban average (77.5/1000)
- Car dependency in Detroit (385.6/1000) slightly above national 
  urban average
- Education and employment are stronger predictors of poverty 
  than racial composition
- Statistically significant transit mode differences across poverty 
  groups (p < 0.001)

## Tools
R · ggplot2 · dplyr · corrplot · US Census data

## Data Sources
Census Bureau tables: B01003, B17001, B08006, B25004, B15003, B23025, B02001
