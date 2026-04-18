# Pharmaceutical Trial Analysis: Tumor Treatment Efficacy

**Tools:** Python | pandas | matplotlib | scipy | Jupyter Notebook  
**Author:** Chris Livesay

---

## Overview

This project analyzes the results of an animal study comparing the effectiveness of multiple drug regimens in treating squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. The study tracked tumor development in 249 mice over 45 days.

**Key Business Question:** Which drug regimens are most effective at reducing tumor volume, and is there a statistically significant correlation between mouse weight and tumor size?

---

## Key Findings

- **Capomulin and Ramicane** showed the greatest tumor volume reduction over the 45-day treatment period.
- **Infubinol and Ceftamin** showed less effectiveness, with higher final tumor volumes.
- A **strong positive correlation (r = 0.84)** was found between mouse weight and average tumor volume for mice treated with Capomulin, suggesting weight is a significant variable in treatment outcomes.
- One potential outlier was identified in the Infubinol treatment group.

---

## Analyses Performed

- Summary statistics table (mean, median, variance, std, SEM) per drug regimen
- Bar charts showing total number of timepoints per drug regimen
- Pie charts showing the distribution of male vs. female mice
- Box plots showing the distribution of final tumor volume for top 4 regimens
- Line plot of tumor volume over time for a single Capomulin mouse
- Scatter plot and linear regression: mouse weight vs. average tumor volume

---

## Repository Structure

```
Matblot-Challenge/
├── Pymaceuticals/
│   ├── pymaceuticals.ipynb    # Main analysis notebook
│   └── data/
│       ├── Mouse_metadata.csv
│       └── Study_results.csv
└── README.md
```

---

## How to Run

1. Clone the repository: `git clone https://github.com/Clivesay1/Matblot-Challenge.git`
2. Install dependencies: `pip install pandas matplotlib scipy jupyter`
3. Open `Pymaceuticals/pymaceuticals.ipynb` in Jupyter Notebook
4. Run all cells in order
