<div align=center>
# 🚴 Yulu Bike Sharing Demand Analysis
</div>
## 📌 Project Overview

This project analyzes the **Yulu Bike Sharing dataset** to understand the key factors influencing bike rental demand. Using **statistical analysis, SQL, and Python-based EDA**, the goal is to extract actionable business insights that can help optimize operations and improve customer experience.

---

## 🎯 Objectives

* Analyze demand patterns across **time, season, and weather**
* Identify key factors influencing bike usage
* Perform **statistical testing (T-test, ANOVA)**
* Build insights for **business decision-making**
* Create a strong **data analyst portfolio project**

---

## 🛠️ Tools & Technologies

* **SQL** – Data cleaning and querying
* **Python** – Data analysis (Pandas, NumPy)
* **Visualization** – Matplotlib, Seaborn
* **Tableau** – Interactive dashboard (optional)

---

## 📂 Dataset Description

The dataset contains hourly bike rental data with the following features:

* `datetime` – Timestamp of rental
* `season` – Season (Spring, Summer, Fall, Winter)
* `holiday` – Whether the day is a holiday
* `workingday` – Whether the day is a working day
* `weather` – Weather condition
* `temp` – Temperature
* `atemp` – Feels-like temperature
* `humidity` – Humidity level
* `windspeed` – Wind speed
* `count` – Total bike rentals (target variable)

---

## 📊 Key Analysis Performed

### 🔹 1. Descriptive Statistics

* Mean, median, and distribution of bike demand
* Seasonal and weather-based demand comparison

### 🔹 2. Exploratory Data Analysis (EDA)

* Demand trends over time (hourly, daily)
* Distribution plots and outlier detection
* Correlation analysis between variables

### 🔹 3. Statistical Testing

* **T-Test** → Working day vs Non-working day demand
* **ANOVA** → Seasonal impact on demand
* **Correlation Analysis** → Relationship between weather variables and demand

---

## 📈 Key Insights

* 🚀 Bike demand is **highest during morning and evening commute hours**
* 🌦️ **Weather significantly impacts demand** — clear weather leads to higher usage
* 🌡️ Temperature shows a **strong positive correlation** with demand
* 📉 High humidity and windspeed reduce bike usage
* 🏢 Working days show **higher and more consistent demand** than weekends

---

## 💡 Business Recommendations

* 📍 Optimize bike availability during **peak hours (8–9 AM, 6–7 PM)**
* 🌧️ Introduce **discounts during bad weather** to maintain demand
* 🎯 Target **working professionals** with subscription plans
* 📊 Use weather forecasts to **predict demand fluctuations**

---

## 📁 Project Structure

```
Yulu-Bike-Analysis/
│
├── data/
│   └── bike_sharing.csv
│
├── sql/
│   └── analysis.sql
│
├── python/
│   └── eda.ipynb
│
├── dashboard/
│   └── tableau_dashboard.twbx
│
├── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/Yulu-Bike-Analysis.git
```

2. Open the dataset in Python or SQL

3. Run:

* SQL scripts for querying
* Jupyter Notebook (`eda.ipynb`) for analysis

4. (Optional) Open Tableau dashboard

---

## 📌 Future Enhancements

* Build **predictive model (Regression / ML)**
* Deploy dashboard using **Streamlit or Power BI**
* Add real-time data integration

---

## 👩‍💻 Author

**Neha Parulekar**
Assistant Professor | Aspiring Data Analyst

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!
