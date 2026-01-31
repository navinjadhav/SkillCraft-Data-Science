# SkillCraft Data Science — Internship Tasks (Portfolio Ready)

This repository contains my internship tasks completed during the **SkillCraft Technology – Data Science Internship**.
Each task is designed to be **offline-friendly** and reproducible (datasets are included locally).

## ✅ Tasks Included

- **Task 01 — Data Visualization**  
  Histogram + bar chart on an age dataset.
- **Task 02 — Titanic EDA (Offline)**  
  Exploratory analysis with missing-value handling and key comparisons.
- **Task 03 — Decision Tree Classification**  
  Train a decision tree model and report metrics + feature importance.
- **Task 04 — Traffic Accident Analysis**  
  Time-series + grouping analysis (day of week / weather).

> Note: Some datasets are **synthetic (learning datasets)** created to keep the project self-contained and runnable without internet.

## 📁 Project Structure

```
SkillCraft-Data-Science-Standard/
├─ data/
│  ├─ ages_sample.csv
│  ├─ titanic_synthetic.csv
│  ├─ bank_marketing_synthetic.csv
│  └─ traffic_accidents_2025_synthetic.csv
├─ tasks/
│  ├─ task01_data_visualization/
│  ├─ task02_titanic_eda/
│  ├─ task03_decision_tree/
│  └─ task04_traffic_analysis/
└─ requirements.txt
```

## 🧰 Tech Stack

- Python
- pandas
- matplotlib
- scikit-learn (Task 03)

## ▶️ How to Run (Recommended)

1) Create a virtual environment (optional but recommended)
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
```

2) Install dependencies
```bash
pip install -r requirements.txt
```

3) Open any notebook and run all cells
```bash
jupyter notebook
```

## 🎯 What I learned

- How to approach a dataset step-by-step (inspect → clean → analyze → visualize)
- Choosing the right plot for the right question
- Basic ML workflow: preprocessing → split → train → evaluate

---

**Author:** Navin Jeevan Jadhav  
**Academic Year:** 2025–26
