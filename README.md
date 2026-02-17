# Credit Risk & Default Prediction Model

## 1. Business Objective
* **Predict Probability of Default (PD):** Developed a model to assess creditworthiness for an NBFC.
* **Risk Categorization:** Segmented customers into Poor, Average, Good, and Excellent categories.
* **Decision Support:** Enabled data-driven loan approvals to support future **Straight Through Processing (STP)**.

## 2. Dataset & Leakage Prevention
* **Data Sources:** Integrated Loan, Personal, and Bureau datasets.
* **Data Integrity:** Performed **Train-Test split before merging** to strictly avoid **data leakage**, ensuring the model generalizes well to unseen data.

## 3. Feature Engineering 🧮
* **Key Metrics:** Calculated LTI Ratio, Delinquency Ratio, Avg DPD, and Months Since Last Delinquency.
* **Feature Selection:** Utilized **Weight of Evidence (WOE)** and **Information Value (IV)** for categorical feature selection, a standard practice in industry scorecard development.

## 4. Model Evaluation 📊
* **Algorithm:** Logistic Regression (chosen for high interpretability and scorecard compatibility).
* **KS Statistic:** **85.98%** (achieved at Decile 2), confirming superior separation between events and non-events.
* **Rank Ordering:** Validated that higher deciles consistently show higher event rates.
* **Metrics:** * **AUC:** 0.98
    * **Gini Coefficient:** 0.96