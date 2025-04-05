# 🫁 Impact of Climate Changes and Air Quality on Asthma-Related Emergency Department Visits in a Tropical Country

This repository contains the data analysis and research workflow from an ongoing project conducted at SingHealth Health Services Research Centre, in collaboration with Duke-NUS Medical School.

The study investigates how **climate variables and air pollution metrics** influence asthma-related emergency department (ED) visits in Singapore — a tropical country with relatively stable climate but recurring transboundary haze events and pandemic disruptions.

---

## 📌 Project Overview

- **Objective**: To analyse the temporal relationship between environmental factors (e.g. temperature, rainfall, PSI, PM2.5) and asthma-related ED visits.
- **Period Studied**: 2015–2024
- **Key Focus Areas**:
  - Climate and pollution trends (using NEA datasets)
  - Time-lagged effects on asthma exacerbations
  - COVID-19 pandemic’s impact on ED visit trends
  - Seasonality and haze-related disruptions

---

## 📊 Methods

- **Data Sources**:
  - Asthma ED visits from the **SingHealth COPD & Asthma Data Mart (SCDM)**
  - Environmental data from **NEA** and **Singapore Meteorological Service**
- **Techniques Used**:
  - Pearson correlation & lagged correlation analysis (lag 0–7)
  - Poisson regression modelling
  - Time series decomposition
  - Python-based exploratory analysis and visualisation

---

## 📈 Key Findings (Summary)

- A **10-unit increase in PSI** is associated with a **~8% increase in asthma ED visits**.
- **Higher temperatures** and **rainfall** are linked to fewer ED visits.
- COVID-19 lockdowns coincided with **sharp reductions in ED visits and pollution levels**.
- **Day 4** showed the strongest lagged association between pollution exposure and ED spikes.
- Periods of **Southwest monsoon and transboundary haze (e.g. 2015, 2019, 2023)** align with ED visit surges.

---

## 🧪 Tools & Libraries

- `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`
- `scikit-learn`, `scipy`
- `jupyter`, `plotly`, `datetime`

---

## 📝 Publications & Submissions

- ✅ **Accepted**: *European Respiratory Society (ERS) Congress 2025*
- ⏳ **In Preparation**: **“Monsoon Seasonality, Air Pollution and Pandemic Disruption of Asthma ED Visits in Singapore”** for SingHealth Duke-NUS Scientific Congress 2025

---

## 📜 Ethics & Data Use

This project was conducted under IRB approval (SingHealth Centralised IRB Ref No. 2017/2950).  
No individual-level patient data is shared in this repository.
