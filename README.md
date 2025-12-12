# NHANES Health Study – STAT 540 Project 3

## Project Overview
This project analyzes data from the NHANES study to explore relationships between [replace with your main variables, e.g., blood pressure, BMI, and age].  
The goal is to [briefly state goal – e.g., identify important predictors of high blood pressure and describe patterns across demographic groups].  
This work was originally completed for STAT 540 Project 3 and is now organized with Git and GitHub for reproducibility.

## Data
- **Source:** NHANES dataset (provided in course materials).
- **File:** `data/original/NHANES.RData`
- **Derived data:** Any data cleaning or feature creation is saved in `data/derived/` (e.g., filtered datasets, recoded variables).

## Project Structure
- `code/` – R scripts or helper functions (if used).
- `data/original/` – Raw NHANES data exactly as provided.
- `data/derived/` – Cleaned or transformed versions of the data.
- `report/ProjectFindings.Rmd` – Main report that contains the analysis, code, and results.
- `report/ProjectFindings.html` – Knit HTML report.

## Methods (short summary)
Briefly describe your methods here – for example:
- Exploratory data analysis with summary statistics and plots.
- Fitting [logistic/linear/other] regression models.
- Model diagnostics and interpretation of key coefficients.

## Results (short summary)
Give 2–3 sentences about the main findings:
- Example: Higher BMI and age were associated with increased risk of hypertension, even after adjusting for sex and smoking status.
- Example: The model correctly classified about XX% of individuals with high blood pressure.

## How to Run
1. Open `report/ProjectFindings.Rmd` in RStudio.
2. Make sure `NHANES.RData` is in `data/original/`.
3. Knit the R Markdown document to HTML.
