# Student Depression Analysis (R)

Mini research project examining whether self-reported anxiety predicts depression in university students, using a public Kaggle dataset and reproducible R analysis.

## Key Findings

- 52.9% of anxious students reported depression vs 25.4% of non-anxious students  
- χ²(1) = 6.40, p = .011  
- Logistic regression: OR = 3.31, 95% CI [1.40, 8.03] – anxiety more than tripled the odds of depression

## Methods (Brief)

- Dataset: *Student Mental Health* (Shariful Islam, 2023) from Kaggle  
- Sample: n = 101 students (after listwise deletion for missing data)  
- Variables:
  - Anxiety (Yes/No → 1/0)
  - Depression (Yes/No → 1/0)
- Analyses:
  - Descriptive statistics (prevalence of depression by anxiety status)
  - χ² test of independence
  - Logistic regression to estimate odds ratio + 95% CI

## Reproducibility

- All analyses conducted in R (v4.5.1) with the **tidyverse** ecosystem  
- Full session info and package versions are included at the end of the report  
- Data source: public, anonymised dataset from Kaggle (Islam, 2023)

## Author

- Parsa Rismanchi – BSc Psychology (Iran)
  


