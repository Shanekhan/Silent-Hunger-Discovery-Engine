# 🥗 Silent Hunger Discovery Engine (SHDE)
### **Predictive Analytics for Micronutrient Deficiency Risk in South Asia (2010–2030)**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Focus-Random%20Forest%20Forecasting-green)
![Domain](https://img.shields.io/badge/Domain-Public%20Health%20%7C%20Economics-red)
![Status](https://img.shields.io/badge/Status-Complete-success)

---

## 📌 Project Overview
"Silent Hunger" (micronutrient deficiency) is a global crisis affecting over 2 billion people. Unlike clinical malnutrition, it is often invisible until irreversible damage occurs. 

The **SHDE Engine** is a research-driven analytical framework that quantifies the relationship between **Macroeconomic Volatility (Food CPI)** and **Biological Outcomes (Anemia, Stunting, Wasting)**. Focusing on the Pakistan-India corridor (2010–2025), this project identifies a critical **12-month "Shadow Effect"** between economic shocks and nutritional decline.

---

## 🚀 Key Discovery: The "Shadow Effect"
One of the primary findings of this research is the **12-month temporal lag**. 
* **The Insight:** Food inflation today does not peak in health markers immediately. 
* **The Window:** There is a one-year window between an economic spike and peak nutritional risk, providing a strategic "Policy Window" for anticipatory intervention.

---

## 🛠 Methodology (The PACE Framework)
The project follows the Google-standard **PACE** (Plan, Analyze, Construct, Execute) workflow:

| Phase | Notebook | Objective | Key Outcome |
| :--- | :--- | :--- | :--- |
| **Plan** | `01_Research_Mapping` | Theoretical framework & hypothesis | Indicator Logic |
| **Analyze** | `02_Data_Acquisition` | Multi-source ingestion & harmonization | Cleaned Longitudinal Data |
| **Construct** | `03_EDA_Statistics` | Feature Engineering & Lag Analysis | Statistical Validation |
| **Execute** | `04_Modeling_Forecast` | Random Forest Modeling & Scenario Projections | **74.4% Accuracy Model** |

---

## 📊 Key Findings & Insights
* **Economic Mediation:** Food CPI is a primary leading indicator of nutritional risk.
* **Regional Sensitivity:** Pakistan shows a higher upward sensitivity to inflation shocks compared to structural baselines in India.
* **Feature Importance:** Random Forest diagnostics identified **Lagged Food CPI** and **Country Baseline** as the most significant predictive signals.



---

## 💻 Tech Stack
* **Languages:** Python (Pandas, NumPy, Scikit-Learn)
* **Visualization:** Seaborn, Matplotlib, Plotly (Dynamic Trend Analysis)
* **Modeling:** Random Forest Regressor, Time-Series Lag Analysis
* **Framework:** PACE Framework for Data Science

---

## 📂 Repository Structure

├── Data/                 # Harmonized Longitudinal Datasets

├── Notebooks/            # End-to-End PACE Pipeline (01-04)

├── Plots/                # High-Resolution Visualizations & Forecasts

├── Report/               # Final Executive Research Brief (PDF/HTML)

├── README.md             # Project Documentation

└── shde_master_engine.xls # Final Processed Master Data


## 🎯 Policy Recommendations

Anticipatory Action: Use the 12-month lag to trigger social safety nets before biological manifestation.

CPI-Linked Support: Calibrate cash transfer programs (e.g., BISP/Ehsaas) to real-time food inflation.

Surveillance: Integrate macroeconomic dashboards with public health monitoring.





## 🤝 Connect & Collaborate

I am a Data Scientist focused on social-impact analytics and public health modeling.  

**Shanzay Khan**

Disclaimer: This project is for research and policy-advocacy purposes and does not constitute clinical medical advice.
