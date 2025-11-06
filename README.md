# Time Series Forecasting for Power Plant Emissions  
### LSTM • XGBoost • SARIMA


The goal of this project is to evaluate forecasting models on U.S. power-plant CO₂ emissions using 27+ years of national emissions data.

---

## 📌 Motivation

The U.S. electric power sector is responsible for ~25% of greenhouse-gas emissions.  
Understanding CO₂ trends is essential for:
- policy & regulation
- grid & utility planning
- climate science
- emissions accounting

This project explores:
- Classical forecasting (SARIMA)
- Machine learning (XGBoost)
- Deep learning (LSTM)

---

## 📊 Dataset

**Source:** EPA eGRID (Emissions & Generation Resource Integrated Database)  
**Years Covered:** 1996–2023  
**Records:** 108,129 plant-year observations

Key variables include:
- CO₂ emissions (tons)
- Electricity generation by fuel type (MWh)
- Efficiency indicators

The dataset shows:
- National CO₂ emissions peaked ~2007
- >30% decline since peak
- Driven by: coal retirements, natural gas expansion, renewable growth

---

## 🧠 Models

| Model  | Type | Notes |
|--------|------|-------|
| SARIMA | Time-series baseline | Seasonal autoregression + differencing |
| XGBoost | Gradient boosting | Requires feature engineering |
| LSTM | Deep learning | Captures nonlinear time dependencies |

---

