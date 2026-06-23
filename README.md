# zinc-flotation-recovery-prediction
Zinc Flotation Recovery Prediction | Exploratory Data Analysis + ML Modeling

A data science and machine learning project focused on predicting **Zinc Recovery (%)** in the froth flotation process using process variables.

---

## Project Overview

This project aims to analyze and model the relationship between various flotation process parameters and zinc recovery. The goal is to:
- Understand key factors affecting zinc recovery through Exploratory Data Analysis (EDA)
- Build accurate predictive models
- Provide actionable metallurgical insights for process optimization

---

## Dataset

The dataset contains flotation process variables including:
- `Feed_Grade_%Zn`
- `pH`
- `Collector_Dosage_g_t`
- `Frother_Dosage_g_t`
- `Air_Flow_Rate_m3_min`
- `Impeller_Speed_RPM`
- `Flotation_Time_min`
- `Zinc_Recovery_%` (Target)

---

## Exploratory Data Analysis (EDA)

### Key Insights from Histograms:
- Feed grade ranges mostly between 3–8% Zn with moderate variability.
- pH varies between 8.5–12.5, indicating room for better control.
- Collector dosage shows wide variation (20–160 g/t), suggesting multiple operating regimes.
- Zinc recovery is generally good (many values >80%), but shows a right skew with a cluster near 95–100%.
- Several variables exhibit multimodal distributions, possibly due to different ore types or circuit configurations.

**Next Steps**: Correlation analysis, scatter plots, outlier detection, and baseline modeling.

---

## Technologies Used

- **Python**
- **Pandas** & **NumPy** (Data manipulation)
- **Matplotlib** & **Seaborn** (Visualization)
- **Scikit-learn** / **XGBoost** (Future modeling)

---

## Project Structure
