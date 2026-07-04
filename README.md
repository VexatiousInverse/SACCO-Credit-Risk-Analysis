# SACCO-Credit-Risk-Analysis
Analyzing SACCO lean defaults and members demographics

## Project Overview
This project is a data analysis pipeline designed to evaulate credit risk and financial demographics for a Saving and Credit Co-operative Organisation (SACCO) operating across five Counties in Kenya. The analysis processes member data and engineers custom risk features.

## Tech Stack & Tools
* **Language:** Python 3
* **Data Manipulation:** `pandas`, `numpy`
* **Statistical Visualization:** `matplotlib`, `seaborn`
* **Automated Reporting:** `weasyprint`, HTML/CSS rendering

  ## Analytical Phases
  **Data Quality Diagonistics:** Identified and handled missing values (MNAR) and validated numerical boundaries for income and loan data.
  **Feature Engineering:** Developed a custom risk assesment model called (`Risk Tier`) evaluating members based on their Loan-to-income ratios.
  **Exploratory Data Analysis (EDA):** Combined metircs by gender and business sector to isolate finanacial exposures.

  ## Strategic Business Insights
  **Risk Concentration:** Isolated a high-risk borrower subset (`Loan_Income_Ratio > 2`) showing a higher elevated default rate compared to baseline sacco Average.
  **Geographic Distribution:** Visualized distinct regional disparities in average savings rates and default occurrences.

  ## Recommendatons
  Based on the quantative analysis evidence, I recommend the implementation of a **Tiered Risk Lending Framework**.
  Rather than enforcing a strict borrowing cap that could stifle portfolio growth, members requesting high-risk loans like that of greater than 200% of monthly income should be flagged for secondary manual underwriting and required to demonstrate a minimum maintained saving rate of 30% to qualify.
  ## Repository Contents
* `sacco.ipynb`: The core Google Colab notebook containing the Python pipeline.
* `/charts/`: High-resolution PNGs generated via Seaborn.
* `cleaned_sacco_data.csv`: The validated dataset used for the final analysis.
  
