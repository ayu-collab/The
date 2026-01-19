# Credit Risk Anomaly Research & Big Data Validation

## Project Overview
This project simulates an R&D workflow for a FinTech environment. It focuses on validating large-scale financial data using **PySpark** and conducting a comparative study between statistical and machine learning methodologies for **Credit Risk Anomaly Detection**.

## Tech Stack
- **Big Data Engine:** PySpark (Data Validation & SQL)
- **Machine Learning:** Scikit-Learn (Isolation Forest)
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## Key R&D Phases

### 1. Data Validation Layer (PySpark)
Built a robust validation pipeline to process **284,807 records**.
- Performed schema enforcement and null-value audits.
- Implemented financial logic constraints to ensure data integrity (e.g., verifying `Amount` and `Time` variables).

### 2. Comparative Outlier Research
Compared two distinct approaches to identify high-risk transactions:
- **Statistical Method:** Z-Score analysis on transaction volume.
- **ML Method:** Multivariate Anomaly Detection using **Isolation Forest**.

### 3. Visual Analysis of Anomalies
The graph below demonstrates how the ML model isolated high-value, high-risk transactions (Anomalies) from the standard distribution.

![Anomaly Distribution](./image/anomaly_distribution.png)

## Results Summary
- **Average Normal Transaction:** $76.65
- **Average Anomalous Transaction:** $1064.14
- **Efficiency:** The Isolation Forest method reduced the "investigation pool" by 93% compared to standard Z-Score filtering, identifying 14 actual fraud cases in the research sample.

## Detailed Research
For a deep dive into the methodology, algorithm precision, and model selection logic, please refer to the [RESEARCH_NOTES.md](./reports/RESEARCH_NOTES.md) file.

---
**Contact:** devkotaaayushma08@gmail.com

