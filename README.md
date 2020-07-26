# Preparing for the GRE: Dos and Donts from a Statistical Standpoint

View the report [here](http://msieviec.github.io/gre_analysis/gre.html).

# Abstract

## Objective

The Graduate Record Examinations (GRE) are a common requirement for acceptance into graduate school. The purpose of this study was to find ways to anticipate GRE scores by analysis of practice test results, as well as to assess how GRE scores are affected by the number of practice tests taken and the number of hours studied.

## Methods

The data were self-reported scores from practice tests and the GRE. Two sources were used: [Practice GRE scores vs. real GRE scores](https://forum.thegradcafe.com/topic/38585-practice-gre-scores-vs-real-gre-scores/page/10/#comments) (The GradCafe) and [What were your real GRE & practice test (Kaplan, Manhattan, Princeton, etc.) scores?](https://www.quora.com/What-were-your-real-GRE-practice-test-Kaplan-Manhattan-Princeton-etc-scores?share=1) (Quora). What was recorded were:

- GRE scores (verbal, quantitative, and analytical writing where available)
- Online practice test scores from:
    - ETS PowerPrep 1 and 2
    - Kaplan 1 and 2
    - Magoosh 1 and 2
    - Manhattan 1 and 2
    - The Princeton Review 1 and 2
- The number of hours an individual studied
- The number of practice tests an individual took (including practice tests of individual sections)

What was not recorded were:

- GRE scores from the old grading system
- Scores from less popular tests (e.g. Barron's)
- Practice test scores without accompanying GRE scores
- Scores of individual practice test sections (e.g. only verbal and no quantitative)
- Scores that were too ambiguous to satisfactorily classify

After exploratory analysis, scores of the different practice tests were compared to the corresponding GRE scores. Analytical writing scores were not divided by the different practice tests as the sample size was too small. Hours studied and tests taken were stratified by quantiles, the GRE Q and V scores of which were compared for significant differences.

## Results

All average GRE scores were found to be at least as high as all average practice test scores, with ETS's PowerPrep 1 and 2 Q scores having no significant difference from GRE scores, indicating their use as the most accurate predictor of GRE scores. The comparison of practice AW scores to GRE scores was inconclusive. V scores were found to be distributed more highly at less than 94 hours studied, with Q scores approaching but failing to reach significance with the same metric. Test takers studying 35-93 hours were found to have the greatest (though still weak) positive correlations with GRE scores. Q and V scores were not found to be distributed differently according to the number of practice tests taken, with no significant correlation found, either.

# Files and Folders
- gre_files/ - images for html document
- gre.Rmd - project R markdown file
- gre.html - project HTML file
- gre_scores.csv - data collected for gre and practice test scores and studying

# Notes 

This analysis was generated using OSX 10.14.5, RStudio v1.1.463, Python 3.7.3, and the following libraries and packages:

This report was generated using OSX 10.15.6, RStudio 1.3.1056, R 4.0.2, and the following libraries:

- bookdown 0.20
- broom 0.7.0
- DT 0.14
- GGally 2.0.0
- ggplot2 3.3.2
- tidyverse 1.3.0

