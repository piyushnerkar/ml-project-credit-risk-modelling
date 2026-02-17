Project Title

Built an end-to-end credit risk model for an NBFC using logistic regression with WOE-based feature selection. Implemented rank ordering, KS statistic, Gini coefficient, and deployed via Streamlit.

2. Business Objective

Explain in 4–5 lines:

Predict probability of default (PD)

Categorize into Poor / Average / Good / Excellent

Enable data-driven loan approval

Support future Straight Through Processing (STP)

This shows business understanding 🧠

3. Dataset Description

Mention:

Loan data

Personal info data

Bureau data

Train-test split done before merging (to avoid leakage 🔥 good point)

Recruiters LOVE when you mention data leakage prevention.

4. Feature Engineering 🧮

Explain clearly:

Loan-to-Income (LTI) Ratio

Delinquency Ratio

Avg DPD per Delinquency

Credit Utilization

Months Since Last Delinquency

Mention:

WOE & IV used for categorical feature selection.

That sounds very industry-ready.

5. Model Used

Logistic Regression

Why chosen (interpretability)

Suitable for scorecard development

6. Model Evaluation 📊

Add:

KS Statistic

Explain briefly how you calculated using deciles.

Rank Ordering

Explain that higher deciles show higher event rates.

ROC Curve

Add screenshot.

Metrics:

AUC: 0.98

Gini: 0.96

KS: 85.98%

These numbers are very strong. 🔥


