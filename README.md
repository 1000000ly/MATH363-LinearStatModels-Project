# Vegetable TVC Profiling and Safety Assessment

This repository contains the submitted coursework for the module **MATH363 - Linear Statistical Models** (2024/25). The analysis investigates total viable counts (TVC) across four vegetable categories using standard linear statistical methods.

## Project Overview

The aim of this assignment is to:

- Assess whether the mean log-transformed TVC differs across vegetable groups using one-way ANOVA.
- Conduct post-hoc comparisons with Tukey's HSD and Bonferroni-adjusted t-tests.
- Estimate group means on both the log and original TVC scales.
- Evaluate model assumptions and provide cautious interpretation of results due to small sample sizes.
- Visualize group distributions using boxplots and summary statistics.

## Methods

- One-way ANOVA (`aov` function in R)
- Multiple comparisons: Tukey HSD, Bonferroni-adjusted t-tests
- Boxplots via `ggplot2`
- Group mean estimation and transformation
- Assumption checks and critical discussion

## Notes

The small sample sizes in each group (≤ 8) may affect the reliability of the t-tests and ANOVA assumptions. Interpretations are supported by both statistical output and visual summaries, with appropriate caution applied.


