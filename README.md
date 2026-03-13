# Clinical Survival Analysis in Python

Survival analysis on the GBSG2 breast cancer dataset using Python. 
Reproduces methodology commonly used in oncology clinical trials 
including Kaplan-Meier estimation, log-rank testing, and Cox 
proportional hazards modeling.

## What this project covers
- Kaplan-Meier survival curves with 95% confidence intervals
- Stratified KM curves by treatment group (hormone therapy vs none)
- Log-rank test for statistical comparison between groups
- Cox proportional hazards model with hazard ratio forest plot
- Full data cleaning and preprocessing pipeline

## Key Findings
- Patients receiving hormone therapy showed significantly better 
  survival (log-rank p < 0.05)
- Hormone therapy associated with ~30% reduction in hazard (HR = 0.70)
- Higher tumor grade and positive lymph nodes were significant 
  predictors of worse outcomes

## Dataset
GBSG2 breast cancer dataset available via the lifelines Python library.  
686 patients, 8 clinical variables including treatment, tumor 
characteristics, and survival outcomes.

## Tools
Python, lifelines, pandas, matplotlib, Jupyter Notebook

## How to run
pip install lifelines pandas matplotlib seaborn jupyter
jupyter notebook clinical-survival-analysis.ipynb
