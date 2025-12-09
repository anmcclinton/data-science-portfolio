# Data Science Portfolio — Adasia McClinton

This repository includes two Quarto-based data science projects. Each project contains both the source `.qmd` file and the rendered HTML report for review.

---

## 1. Tools for Data Science (CAP5756) — R, SQL, and Python Analysis

**Files**
- Final_Project_CAP5756.html  
- Final_Project_CAP5756.qmd  

**Description**  
This project analyzes flight delay patterns using data from the `nycflights13` package. The same analytical questions are solved using R, SQL, and Python to validate results across languages. The report includes data wrangling, table joins, aggregated summaries, and visualizations of airline performance and delay trends.

**Skills demonstrated**
- Multi-language workflow (R, SQL, Python)  
- Data wrangling with `dplyr` and `pandas`  
- SQL joins and aggregations  
- Data visualization using ggplot2, seaborn, and matplotlib  
- Reproducible reporting with Quarto  

---

## 2. Cognitive Decline and Brain Health — Linear Mixed Models (LMM)

**Files**
- BDP_slides.html  
- BDP_slides.qmd  

**Description**  
This project investigates cognitive decline using the OASIS longitudinal MRI dataset. Using R, several Linear Mixed Models were fit to evaluate the impact of age, dementia severity, socioeconomic status, and brain volume on cognitive performance (MMSE scores). The project includes exploratory visualizations, baseline descriptive tables, missing data handling, and advanced model interpretation.

**Key components**
- Baseline characteristics table created with the `tableone` package  
- Visualizations of age, gender, SES, and brain volume trends  
- Missing data imputation using the `mice` package  
- Linear Mixed Models fit with `lme4` and pooled using `mitml`  
- Final model identified dementia severity (CDR) as a strong predictor of cognitive decline and normalized whole brain volume (nWBV) as a protective factor  

**Skills demonstrated**
- Longitudinal data analysis  
- Linear Mixed Model development and interpretation  
- Data cleaning and missing data techniques  
- R-based statistical analysis and visualization  
- Scientific reporting in Quarto  

---

## How to View the Reports

To view any project:
1. Download the HTML file  
2. Open it in your web browser  

To re-render any `.qmd` file (requires Quarto):
```bash
quarto render filename.qmd


contact: adasiamcclinton@gmail.com
