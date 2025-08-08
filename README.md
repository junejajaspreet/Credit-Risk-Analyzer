# 🏦 Credit Risk Analyzer - EDA Project

This project applies **Exploratory Data Analysis (EDA)** to real-world financial data to analyze **credit risk**. The goal is to identify customer patterns and drivers of loan default to assist banks in making smarter loan decisions.

---

## 📌 Problem Statement

Banks often lose money either by:
- ❌ Rejecting reliable customers, or
- ✅ Approving loans for customers who default.

This project helps solve that by:
- Understanding which client attributes indicate **payment difficulties**
- Comparing profiles of **defaulters vs. non-defaulters**
- Using data-driven analysis to support loan approval decisions

---

## 📁 Data Sources

| File | Description |
|------|-------------|
| `application_data.csv` | Client info at time of loan application |
| `previous_application.csv` | Client’s history of past loan approvals/refusals |
| `columns_description.csv` | Data dictionary for all variables |

---

## 🧠 Analysis Objectives

- Handle missing values with proper strategy
- Detect and reason about outliers
- Analyze class imbalance in the target (`TARGET`)
- Perform univariate, bivariate, and segmented analysis
- Use correlation analysis to find strong variable relationships
- Visualize findings using Python plots

---

## 🔎 Key Insights

- **Defaulting clients** often have:
  - Lower income
  - Higher credit amounts
  - Different contract types
- **Imbalanced data**: Defaulters form a minority → important for business risk
- **Top correlated variables** differ for defaulters and non-defaulters → useful for modeling

---

## 📊 Visualizations

- Histograms, Boxplots, KDE plots
- Countplots for categorical features
- Heatmaps for correlation
- Comparison plots for `TARGET` classes

---

## 📦 Tools Used

- Python
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
- Jupyter Notebook
- Excel for data dictionary
- Tableau (optional aesthetic plots for presentation)

---

## 📄 Deliverables

- `EDA Credit Risk Analyzer - Project.ipynb` – Full EDA with code and markdown
- `CreditRiskAnalyzer_Presentation.pdf` – Summary presentation with key charts and business interpretation

---

## ✍️ Author

**Jaspreet Singh Juneja**  
Student at UpGrad | Data Science Learner

---


## Dataset
The full dataset is too large to store in GitHub due to file size limits.  
You can download it here: [Google Drive Link](https://drive.google.com/file/d/18kbCXj97jxvYFe1KmWnRZ7YVtL8WlHcm/view?usp=sharing)

