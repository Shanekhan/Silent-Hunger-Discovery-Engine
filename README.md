# Silent Hunger Discovery Engine (SHDE)
### Predictive Analytics for Micronutrient Deficiency Risk in South Asia

## 📌 Project Overview
"Silent Hunger" (micronutrient deficiency) affects over 2 billion people globally. Unlike visible malnutrition, it often remains undetected until irreversible health damage occurs. 

The **Silent Hunger Discovery Engine (SHDE)** is a research-driven analytics project that integrates public health indicators, economic stress signals, and nutritional trends to predict population-level risk. This project focuses specifically on **Pakistan and India (2010–2025)** to understand how economic factors like food inflation drive nutritional outcomes.

---

## 🔍 Key Research Questions
1. **Temporal Trends:** How have anemia, stunting, and wasting prevalence evolved over the last 15 years?
2. **Economic Correlation:** Does high Food CPI (Inflation) directly correlate with increased nutritional deficiency?
3. **Risk Mapping:** Which demographics remain at the highest risk despite national-level progress?
4. **Predictive Analytics:** Can we forecast nutritional risk for 2030 based on current socio-economic trajectories?

---

## 🛠 Methodology & Roadmap

### **Notebook 01: Research & Problem Mapping**
* **Objective:** Define the theoretical framework and domain-specific hypotheses.
* **Key Tasks:** Literature review on micronutrient gaps and defining the "Silent Hunger" index.
* **Outcome:** A structured list of indicators and established research assumptions.

### **Notebook 02: Data Acquisition & Harmonization**
* **Objective:** Ingest and standardize "messy" raw data from global sources.
* **Sources:** WHO (Anemia), UNICEF (Stunting/Wasting), World Bank (Food CPI).
* **Process:** Metadata bypassing, sheet targeting, and **Wide-to-Long** schema transformation (Melt logic).

### **Notebook 03: Exploratory Data Analysis (EDA) & Statistics**
* **Objective:** Uncover patterns, handle outliers, and perform statistical profiling.
* **Key Tasks:** Correlation analysis between Inflation and Nutrition; handling missing temporal data.
* **Outcome:** Feature selection and a "Clean Master Dataset."

### **Notebook 04: Predictive Modeling & Risk Scoring**
* **Objective:** Develop an explainable ML framework to forecast risk levels.
* **Models:** Time-series forecasting and regression-based risk scoring.
* **Final Output:** A comprehensive Research Report with data-driven policy recommendations.

---

## 💻 Technology Stack
* **Language:** Python 3.x
* **Data Science:** Pandas, NumPy, Scipy
* **Machine Learning:** Scikit-Learn
* **Visualization:** Seaborn, Matplotlib, Plotly (Interactive Research Charts)
* **Documentation:** Jupyter Notebooks & Markdown

---

## 🎯 Scope & Ethics
* **Level:** Population-level analysis (National/Regional).
* **Non-Clinical:** This engine is designed for research and policy support, not for individual medical diagnosis.
* **Transparency:** All data cleaning steps and model assumptions are fully documented to ensure reproducibility.

---

## 🤝 Collaboration & Contact
This is an open-access research project. Feedback from Data Scientists, Economists, and Public Health experts is welcome.

**Shanzay Khan** [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/shanzaykhan-/)
