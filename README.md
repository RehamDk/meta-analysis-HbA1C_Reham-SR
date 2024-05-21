# Meta-Analysis of HbA1c

combine results from studies with complete reported data to derive a pooled estimate of the effect size, and perform sensitivity test

The analysis involves:
1. Extracting HbA1c data
2. meta-analysis using the `metafor` package.
4. Conducting sensitivity analyses, including leave-one-out analysis

## Data
Of complete reported studies 
- Sample sizes
- Means
- Standard deviations of HbA1c levels for both control and intervention groups
For the whole systematic review we included 15 studies, 10 of them reported quantitative measures for HbA1c, and only 6 reported complete data

## Used packages
- `metafor`: For conducting the meta-analysis.
- `ggplot2`: For creating plots.
