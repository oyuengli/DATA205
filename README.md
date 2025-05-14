# DATA 205 Capstone Project: Food Inflation & Household Expenditure Analysis

**Author:** Olivia Yuengling
**Course:** DATA 205, Prof. Perine
**Date:** May 2025

---

## 📖 Project Overview

Over the past decade, U.S. food prices have risen faster than overall inflation, putting disproportionate strain on low‑income households. This capstone analyzes:

1. How food prices compare to core CPI (ex‑food & energy) from 2013–2023.
2. Which food categories spike most during high‑inflation years.
3. Seasonal volatility across food groups.
4. Household spending patterns by income group and their year‑over‑year growth.

Ultimately, we identify who bears the brunt of food inflation and which items they can no longer afford.

---

## 📂 Repository Structure

```
├── README.md               # Project overview and instructions
├── Data Files/                    # Raw and processed data files
│   ├── core_inflation_1983-2025.csv
│   ├── average_prices.csv
│   ├── combined_interview_data.csv
│   └── food_expenditure_summary.csv
├── DATA 205 Project Code          # R and Python scripts and functions
│   ├── 01_data_ingestion.R  # Data loading & cleaning functions
│   ├── 02_EDA.Rmd           # Exploratory Data Analysis (R Markdown)
│   ├── 03_analysis.Rmd      # Statistical tests & modeling
│   └── utils.R              # Reusable functions (themes, palettes)
├── reports/                 # Outputs
│   ├── final_report.pdf     # Written report
│   └── presentation.pptx    # Slide deck
```

---

## 🚀 Getting Started

### Prerequisites

* R (>= 4.0)
* Python (>= 3.10)
* RStudio (recommended)
* Packages: tidyverse, ggplot2, highcharter, viridis, lubridate, corrplot

Install packages in R:

```r
install.packages(c("tidyverse","highcharter","viridis","lubridate","corrplot"))
```

### Running the Analysis

1. Clone this repo:

   ```bash
   ```

git clone [https://github.com/yourusername/data205-food-inflation.git](https://github.com/yourusername/data205-food-inflation.git)
cd data205-food-inflation

```
2. Place raw CSVs into `data/` (as named above).
3. In RStudio, open and run **R/01_data_ingestion.R** to clean & merge datasets.  
4. Knit **R/02_EDA.Rmd** to generate exploratory figures and tables.  
5. Knit **R/03_analysis.Rmd** for statistical tests and modeling results.  
6. Review outputs in `reports/` and save final artifacts.

---

## 🗂️ File Descriptions

- **01_data_ingestion.R**: loads CSVs, defines column types, cleans CE interview data, merges CPI & food-price datasets, outputs `food_expenditure_summary.csv`.
- **02_EDA.Rmd**: R Markdown documenting data exploration—time series, seasonal patterns, deviation analysis, volatility, income‐group trends, heatmaps.
- **03_analysis.Rmd**: correlation matrix, regression models, ANOVA tests, and interpretation of results.
- **utils.R**: custom ggplot theme (`theme_food`), color palettes, reusable data‐processing functions.
- **reports/**: compiled PDF report and presentation deck for submission.

---

## 📈 Key Findings
1. **Food prices rose faster than core CPI**, with beef and dairy showing the largest deviations in 2021–2023.  
2. **Staples (grains, pantry items) remained stable**, suggesting substitution by budget‐constrained households.  
3. **Lower‑income groups experienced the steepest spending growth**, while top earners plateaued spending post‑2020.  
4. **Seasonal volatility** is highest in meats and produce, lowest in staples.

These insights guide policy recommendations on targeted food assistance and pricing interventions.

---

## 🤝 Collaboration & License
This work is released under the MIT License – see `LICENSE` for details.  
Feel free to fork and adapt with attribution.  

For questions or data access issues, contact Olivia at olivia.yuengling@example.com.

```
