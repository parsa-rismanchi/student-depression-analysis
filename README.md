Student Depression Analysis (R)

The study will examine the relationship between self-reported anxiety and the presence of depression in university students. The research will employ a Kaggle dataset and is reproducible in R.

Key Findings
- A higher percentage of students who experienced anxiety also had depressive symptoms compared with non-anxious peers—approximately one in two students with anxiety symptoms compared with one in four non-anxious students.
- A chi-squared test of independence (2x2 contingency table; no continuity correction) revealed a significant link between anxiety and depression. This is reflected in the knitted report under χ² and p-values.
- The logistic regression analysis showed that students who suffered from anxiety were much more likely to report depression (OR = 3.31, 95% CI: 1.40 to 8.03).

Techniques (Brief)
- Dataset: Student Mental Health dataset (Shariful Islam, 2023), sourced from Kaggle.
- Sample: Final analytic sample of 101 students after eliminating cases with missing answers.
- Variables:
  - Anxiety (0 = No, 1 = Yes)
  - Depression (0 = No, 1 = Yes)
- Analyses:
  - Descriptive statistics for prevalence calculation of depression by anxiety status.
  - Chi-squared test of independence to compare groups (2x2 table; no continuity correction).
  - Logistic regression to estimate odds ratios and 95% confidence intervals.

Reproducibility
- Requirements: R (4.0+ preferred) and the packages tidyverse, knitr, broom.
- To replicate, copy `student_mental_health.csv` into your project folder and kn
