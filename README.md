# MLB Streamer Fantasy Prediction

This repository contains a multivariate statistics project analyzing 2025 MLB starting pitcher streaming outcomes.

The project uses pitcher start-level data to examine whether pre-start information can help explain or predict fantasy baseball performance. The analysis focuses on dimensionality reduction, clustering, and supervised prediction.

## Project Overview

The main goal of this project is to evaluate patterns in MLB pitcher streaming outcomes using multivariate methods. Instead of looking at one variable at a time, the project combines several pitcher, matchup, and timing variables to see how they relate to fantasy point outcomes.

The report includes:
- exploratory data analysis,
- principal component analysis,
- clustering,
- random forest prediction,
- variable importance analysis,
- and predicted vs. observed outcome comparison.

## Methods Used

### Principal Component Analysis
PCA was used to reduce correlated pre-start variables into a smaller set of components. This helped summarize broader patterns in the data, such as recent performance, workload, and matchup context.

### Clustering
Clustering was used to group pitcher starts with similar profiles. The goal was to see whether certain types of streaming situations produced better or worse fantasy outcomes.

### Random Forest
A random forest model was used to predict fantasy points from the available start-level variables. Variable importance was used to identify which predictors contributed most to the model.

## Tools Used

- R
- Quarto
- tidyverse
- ggplot2
- tidymodels / modeling tools
- PCA
- clustering
- random forest

## Files

- report.pdf — Final written report with analysis, tables, and plots
- analysis.qmd — Quarto source file used to generate the report
- data/ — Data files used for the project, if shareable
- figures/ — Exported plots or report visuals, if included

## Notes

This project was completed for a multivariate statistics course and is included as a public example of applied sports analytics, statistical modeling, and reproducible reporting in R.

Some raw data collection steps may not be fully included if the original source files were manually assembled or not intended for redistribution.
