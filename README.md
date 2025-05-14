# 📊 DATA 205 Capstone Project: Food Inflation & Household Expenditure Analysis
**Author:** Olivia Yuengling  
**Course:** DATA 205, Prof. Perine  
**Date:** May 2025

## 📖 Project Overview
Over the past decade, U.S. food prices have risen faster than overall inflation, placing disproportionate strain on low‑income households. This capstone analyzes:

- How food prices compare to core CPI (excluding food & energy) from 2013–2023  
- Which food categories spike most during high‑inflation years  
- Seasonal volatility across food groups  
- Household spending patterns by income group and their year‑over‑year growth  

**Goal:** Identify which groups are most affected by food inflation and which items are becoming unaffordable for them.

---

## 📂 Repository Structure

├── README.md # Project overview and instructions

├── Data Files/ # Raw and processed data files

│ ├── core_inflation_1983-2025.csv

│ ├── average_prices.csv

│ ├── ces_data.csv

│ └── food_expenditure_summary.csv

├── DATA 205 Project Code/ # R and Python scripts

│ ├── 01_data_ingestion.Rmd # Data loading & cleaning functions

│ ├── 02_EDA.Rmd # Exploratory Data Analysis

│ ├── 03_DATA_205_Yuengling_Analyses.Rmd # Statistical tests & modeling

│ └── ces_data_load.ipynb # CES data preprocessing (Python)

├── reports/ # Output documents

│ ├── DATA205_33334_Yuengling_FinalReport.docx

│ └── DATA205_33334_Yuengling_Presentation.pptx


---

## 🚀 Getting Started

### Prerequisites

- R (>= 4.0)  
- Python (>= 3.10)  
- RStudio (recommended)
- Google Colab or Microsoft VS (recommended)

### Required R Packages

```r
install.packages(c("tidyverse", "highcharter", "lubridate", "corrplot", "dplyr", "ggplot2", "stringr", "readr", "tidyr", "scales"))
```
## 🛠️ Running the Analysis

1. Clone this repository.
2. Place raw `.csv` files into the `Data Files/` directory using the exact file names listed above.
3. Open RStudio and run `01_data_ingestion.Rmd` to clean and merge the datasets.
4. Knit `02_EDA.Rmd` to generate exploratory data visuals and tables.
5. Knit `03_DATA_205_Yuengling_Analyses.Rmd` to run statistical tests and modeling.
6. Review outputs in the `reports/` directory.

---

## 🗂️ File Descriptions

- **01_data_ingestion.Rmd**: Loads and cleans CES & CPI datasets, merges data, outputs `food_expenditure_summary.csv`.
- **02_EDA.Rmd**: Time series, seasonal patterns, income trends, heatmaps, volatility analysis.
- **03_DATA_205_Yuengling_Analyses.Rmd**: Correlations, regressions, ANOVA, and interpretations.
- **utils.R**: Custom `ggplot2` theme (`theme_food`), color palettes, reusable data-wrangling functions.
- **reports/**: Final project report and presentation deck.

---

## 📈 Key Findings

- Food prices outpaced core CPI, especially in **2021–2023**. Beef and dairy showed the largest deviations.
- **Staples** (e.g., grains, pantry goods) remained stable — likely substituted in by budget-constrained households.
- **Low-income groups** saw the **steepest spending growth**, while **high-income households** plateaued after 2020.
- **Seasonal price volatility** was highest in **meats and produce**, and lowest in **staples**.

---

## 🎯 Implications

These findings inform **targeted food assistance policies** and support strategic interventions in food pricing and access — especially for vulnerable, low-income populations.

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [GitHub](#https://github.com/oyuengli) or [LinkedIn](#https://www.linkedin.com/in/olivia-yuengling/).

