# Student Depression Analysis (R)

This project examines whether self-reported anxiety is associated with depression among university students. The analysis is based on an open-access dataset from Kaggle and is fully reproducible using R.

## Key Findings
- Over half of students reporting anxiety also reported depressive symptoms, compared with approximately one quarter of non-anxious students.
- A two-proportion test indicated a significant association between anxiety and depression, χ²(1) = 6.40, p = .011.
- Logistic regression showed that students reporting anxiety had substantially higher odds of reporting depression (OR = 3.31, 95% CI [1.40, 8.03]).

## Methods (Brief)
- **Dataset:** Student Mental Health dataset (Shariful Islam, 2023), sourced from Kaggle.
- **Sample:** Final analytic sample of 101 students after removal of missing responses.
- **Variables:**
  - Anxiety (0 = No, 1 = Yes)
  - Depression (0 = No, 1 = Yes)
- **Analyses:**
  - Descriptive statistics to estimate depression prevalence by anxiety status.
  - Two-proportion test reported as a chi-squared statistic.
  - Logistic regression to estimate odds ratios and 95% confidence intervals.

## Reproducibilit
