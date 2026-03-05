#  BA830 Jenga Incentive Experiment

##  Boston University - Questrom School of Business
### BA830: Business Experimentation and Causal Methods | Team 12

---

##  Project Overview

This repository contains the analysis code and data for our experimental study examining how different incentive structures affect task performance on a Jenga tower building task.

**Research Question:** *Do performance-based incentives lead to faster task completion compared to flat compensation or no compensation?*

---

##  Experimental Design

| Group | Incentive | Description |
|-------|-----------|-------------|
| **Control** | None | Asked to build tower with no reward mentioned |
| **Treatment 1** | Flat candy | Offered a chocolate piece for completing the task |
| **Treatment 2** | Bonus candy | Offered chocolate + extra chocolate if completed under 35 seconds |

**Sample Size:** 91 participants

---

##  Key Findings

- **Control group mean:** 45.62 seconds
- **Treatment 1 (Flat) mean:** 44.76 seconds (-0.86s, p=0.788)
- **Treatment 2 (Bonus) mean:** 41.43 seconds (-4.20s, p=0.140)

While the bonus group was ~4 seconds faster on average, results were not statistically significant at conventional levels.

---

##  Methods Used

- Randomized Control Trial (RCT) with blocking by gender
- Average Treatment Effect (ATE) estimation
- Heterogeneous Treatment Effects (CATE) with interactions
- Intent-to-Treat (ITT) and Per-Protocol analysis
- Power analysis and uncertainty quantification

---

##  Team Members

- Yashaswini Reddy
- Sambisha Godi
- Yuanhao Li
- Abdul Majid
- Samuel Buelvas

---

##  Files in This Repository

| File | Description |
|------|-------------|
| `Jenna Tower Datasets.csv` | Raw experimental data |
| `[B1_Team_12_Build a Tower and Get Some Candy: The Effect of Bonus Compensation on Productivity].ipynb` | Complete analysis notebook |
| `README.md` | This file |

---

##  How to Run

1. Open the Jupyter notebook in Google Colab or Jupyter Lab
2. Run all cells to reproduce the analysis
3. Data is already loaded in the notebook

---

##  Course Information

**Course:** BA830 - Business Experimentation and Causal Methods  
**Term:** Spring 2026  
**Institution:** Boston University

---

##  Acknowledgments

Thanks to all 91 participants who built Jenga towers for chocolate!