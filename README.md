Student Depression Analysis (R)

A small study checking if student anxiety levels link to depression, based on personal reports. The data comes from Kaggle - free to access. Analysis is done in R, with every step repeatable by others. Focus stays on real results, no guesswork.

Key Findings

Over half of stressed pupils said they felt down, while one in four calm students did.
χ²(1) was 6.40, while p hit .011
- Logistic regression showed: OR = 3.31, 95% CI [1.40, 8.03] - so, when anxiety's present, chances of depression go way up. Instead of just doubling, they jump by over three times. That link stays clear within the confidence range. No fluff needed - it’s a solid signal. Not a guess, but data pointing one direction

Methods (Brief)

- Dataset: Student Mental Health (Shariful Islam, 2023) from Kaggle
- Example: n = 101 learners, once gaps were removed from records
- Variables:
Anxiety present? Use 1 if yes, 0 if no
- Mood low? (Yep/Nah → 1/0)
- Analyses:
- Summary numbers (how common depression is depending on whether anxiety is present or not)
χ² test to check if variables are linked
- Logistic regression used to figure out odds ratio along with 95% confidence interval

Reproducibility

All analyses done in R (v4.5.1), using tools from the tidyverse suite
- Check the full details on sessions and software versions right at the close of this write-up
- Source of data: publicly available, anonymous info from Kaggle (Islam, 2023)                                            English phrasing was lightly edited using language tools
Author

- Parsa Rismanchi – BSc Psychology (Iran)
