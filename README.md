# 💊 Pymaceuticals Inc. – Drug Trial Analysis

## 🧪 Overview

This project analyzes the results of a fictional pharmaceutical company's preclinical trials for various anti-cancer medications. The goal is to assess the effectiveness of different drug regimens on tumor volume reduction in mice.

We use Python, Pandas, and Matplotlib to clean and visualize the clinical trial data, generating summary statistics and comparative plots.

---

## 🧰 Technologies Used

- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📁 Project Files

```
Pymaceuticals-Inc/
├── pymaceuticals_starter.ipynb   # Notebook with full analysis and plots
├── data/
│   ├── Mouse_metadata.csv        # Mouse trial metadata
│   └── Study_results.csv         # Drug response over time
└── README.md                     # Project documentation
```

---

## 🔬 Analysis Objectives

- Merge and clean mouse metadata and study results
- Remove duplicate or invalid entries
- Calculate:
  - Mean, median, variance, std, SEM for tumor volumes
  - Summary stats for top 4 promising treatments
- Generate:
  - Line plots of tumor volume over time
  - Bar plots showing number of timepoints
  - Box plots comparing final tumor volume across treatments
  - Scatter plots and correlation stats for Capomulin

---

## 📈 Key Insights

- **Capomulin and Ramicane** were the most effective treatments in reducing tumor volume.
- Strong correlation observed between mouse weight and tumor volume under Capomulin regimen (r ≈ 0.84).
- Visualizations show consistent tumor suppression across trials for the most effective drugs.

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/Geo222222/Pymaceuticals-Inc.git
cd Pymaceuticals-Inc
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook pymaceuticals_starter.ipynb
```

3. Run the analysis and review plots/outputs.

---

## 📌 Future Work

- Run statistical tests to compare treatment efficacy (t-test, ANOVA)
- Build interactive dashboards with Plotly or Dash
- Add survival analysis over time

---

**Author:** [Geo222222](https://github.com/Geo222222)  
**Focus:** Bioinformatics • Data Analysis • Visualization

