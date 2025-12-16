# Student Depression Analysis (R)

In this study, the research question being addressed is whether there is a **relationship** between reported anxiety and reported depression among university students.

The data used in the research is from an open-access Kaggle dataset.

## Key Findings
- More than half of students reporting anxiety also reported depressive symptoms, whereas about one quarter of non-anxious students did.
-A chi-squared test of independence on a 2×2 table (no continuity correction) indicated a relationship between anxiety and depression, χ²(1) = 7.57, p = 0.00594.
- In logistic regression analysis, it was found that students who reported experiencing anxiety had higher odds of reporting depression (OR = 3.31, 95% CI [1.40, 8.03]).

## Methods (Brief)
- **Dataset:** Student Mental Health Dataset (Shariful Islam, 2023) obtained through Kaggle.
- **Sample:** Final analytic sample of **101** students after excluding missing data for the variables of interest.
- **Variables:**
  - Anxiety (0 = No, 1 = Yes)
  - Depression (0 = No, 1 = Yes)
- **Analyses:**
  - Descriptive statistics for estimating the prevalence of depression by anxiety status.
  - Chi-squared test of independence (2x2 contingency table; no continuity correction).
  - Logistic regression for estimating odds ratios and 95% confidence intervals.

## Notes / Interpretation
- Findings are based on **associations** from a cross-sectional, self-report dataset and cannot establish causality.
- The results may be affected by other uncontrolled factors (e.g., stress levels, sleeping patterns, academic pressures) not accounted for in this simplified model.

## Reproducibility / Requirements
- **R:** version 4.0+ preferred
- **Packages:** tidyverse, knitr, broom
- **To reproduce:**
  1. Ensure `student_mental_health.csv` is in your working directory (project folder).
  2. Knit the `.Rmd` file to HTML or PDF.
