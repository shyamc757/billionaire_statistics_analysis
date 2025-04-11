# 🌍 Billionaire Statistics Analysis

This project performs a statistical investigation into global billionaire trends using a comprehensive dataset from 2023. By applying hypothesis testing techniques on a sample and comparing results with the full dataset, the accuracy and reliability of the statistical inferences are evaluated.


## 📊 Project Goal

To determine whether statistical tests (t-tests, F-tests, etc.) performed on a random sample can accurately reflect the results from the full population dataset of billionaires.


## 📁 Dataset Overview

- **Source**: Forbes-style dataset on 2,640 billionaires across 70+ countries.
- **Key Features**:
  - `finalWorth`: Net worth in USD
  - `selfMade`: Indicates if the billionaire is self-made
  - `age`, `country`, `industry`, `GDP`, `CPI`, etc.
- **Files**:
  - `Billionaires Statistics Dataset.csv` – Full dataset
  - `Sampled Billionaires Statistics Dataset.csv` – Random 1500-sample subset


## 🧪 Statistical Questions Explored

1. **Mean Comparison**: Is the average net worth of self-made billionaires different from those who inherited their wealth?
2. **Age Comparison**: Is the average age of U.S. billionaires different from those in China?
3. **Variance Analysis**: Is the variance in net worth lower among self-made billionaires?
4. **Correlation Check**: Is there a significant correlation between a country’s GDP and the billionaire’s net worth?
5. **Proportion Test**: Is the proportion of self-made billionaires different in Eastern vs Western regions?


## 🛠 How to Run

### Requirements
- R version ≥ 4.0.0
- Recommended: RStudio
- R Packages:
  - `ggplot2`, `dplyr`, `tidyr`, `readr`, `stats`

### Steps
1. Clone the repo
2. Open `stats_project.Rmd` in RStudio
3. Knit to HTML or PDF to generate the analysis report


## 📂 Repository Structure

```
billionaire-statistics-analysis/
│
├── data/
│   ├── Billionaires Statistics Dataset.csv
│   └── Sampled Billionaires Statistics Dataset.csv
│
├── code/
│   ├── stats_project.Rmd
│   └── extra.Rmd
│
├── reports/
│   ├── statsProject.pdf
│   ├── stats_project.pdf
│   └── extra.pdf
│
├── README.md
├── .gitignore
└── LICENSE
```


## 📈 Results Summary

-  No significant difference in average wealth between self-made and inherited billionaires (sample aligns with population).
-  Significant age difference between U.S. and Chinese billionaires.
-  Variance in self-made billionaire wealth is statistically lower.
-  No strong correlation between country GDP and billionaire wealth.
-  Higher proportion of self-made billionaires in Eastern countries.


## 👨‍💻 Authors

Shyam Shah, Manasvi Patwa, Jaimin Shah, Sai Mourya Buchi  


## 📜 License

MIT License. See `LICENSE` for details.
