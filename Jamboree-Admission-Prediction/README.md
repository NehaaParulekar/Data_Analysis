# Graduate Admission Prediction Model

## 📌 Executive Summary
This project builds a predictive linear regression model to estimate graduate admission probabilities for students applying to international universities[cite: 2]. 

## 📉 Business Problem
Educational consultancies need to help students understand their competitiveness before applying[cite: 2]. The objective is to identify the critical academic and profile factors influencing admission chances and build a reliable, interpretable predictive model[cite: 2].

## 🛠 Methodology
* **Algorithm Selection:** Linear Regression (OLS), Ridge, and Lasso Regression using Python (Scikit-Learn, Statsmodels)[cite: 2].
* **Assumption Validation:** Rigorously validated linear regression assumptions, including checking for Multicollinearity (VIF), Linearity, and Homoscedasticity (Breusch-Pagan test)[cite: 2].
* **Evaluation Metrics:** Evaluated model performance using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Adjusted R²[cite: 2].

## 📊 Key Findings
* **Model Accuracy:** The OLS model explains 82.1% of the variation in admission chances (R² = 0.821)[cite: 2]. 
* **Primary Drivers:** CGPA is the strongest positive predictor for admission, followed closely by GRE and TOEFL scores[cite: 2].
* **Secondary Drivers:** Letters of Recommendation (LOR) and Research experience also significantly influence admission chances[cite: 2].
* **Insignificant Variables:** University Rating and Statement of Purpose (SOP) were not statistically significant after controlling for other variables[cite: 2].

## 💡 Recommendations
* **Decision Support:** Educational consultants can use this model to estimate admission probabilities and recommend suitable universities[cite: 2].
* **Targeted Improvement:** Applicants should focus primarily on maximizing CGPA and standardized test scores, as these hold the heaviest statistical weight[cite: 2].

📄 **[Read the full PDF Case Study Here](./Jamboree_case_study.pdf)**
