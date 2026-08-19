# Personal Loan Underwriting & Credit Risk Optimization

## 📌 Executive Summary
This project develops a logistic regression model to automate and optimize the underwriting process for personal loans[cite: 3]. The model predicts default risk to help assign risk-adjusted terms and minimize Non-Performing Assets (NPAs)[cite: 3].

## 📉 Business Problem
The underwriting layer must decide whether to extend credit to an applicant (Fully Paid vs. Charged Off) and determine optimal interest rates, loan tenure, and credit limits based on the predicted default risk[cite: 3].

## 🛠 Methodology
* **Predictive Modeling:** Built a Logistic Regression model using Python (Statsmodels, Scikit-Learn)[cite: 3].
* **Imbalanced Data Handling:** Applied class weight balancing to address the 4:1 imbalance between Fully Paid and Charged Off loans[cite: 3].
* **Feature Engineering:** Handled missing values, capped extreme outliers (99th percentile), resolved multicollinearity by dropping redundant variables, and managed quasi-complete separation issues[cite: 3].
* **Performance Evaluation:** Evaluated using ROC-AUC, PR-AUC, and optimized the F1 threshold for NPA minimization[cite: 3].

## 📊 Key Findings
* **Model Performance:** The model achieved an excellent global ranking capacity with a ROC-AUC score of 0.9015 and a PR-AUC of 0.7701[cite: 3].
* **Risk Escalators:** Higher Debt-to-Income (DTI) ratios and longer loan terms (60 months) drastically increase default risk[cite: 3]. Default frequency escalates monotonically across lower credit subgrades[cite: 3].
* **Protective Factors:** Higher annual income and an established, deep credit history act as significant buffers against default[cite: 3].

## 💡 Recommendations
1. **Hurdle Underwriting:** Implement a two-stage hurdle model featuring an Auto-Approve zone, an Auto-Reject zone, and a Grey zone requiring alternative data verification[cite: 3].
2. **DTI Capping:** Enforce dynamic DTI capping based on the loan term[cite: 3].
3. **Early Warning System:** Monitor changes in credit line openings to trigger preemptive debt restructuring interventions[cite: 3].

📄 **[Read the full PDF Case Study Here](./LoanTAp_Logistic_REgression_case_study.pdf)**
