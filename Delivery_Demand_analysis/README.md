# Delhivery Logistics Performance & Route Optimization

## 📌 Executive Summary
This business case analyzes shipment movement data across Delhivery's logistics network to evaluate operational efficiency and compare actual delivery performance against OSRM (Open Source Routing Machine) estimations[cite: 5]. 

## 📉 Business Problem
As one of India's largest logistics companies, Delhivery handles millions of shipments[cite: 5]. The goal of this analysis is to identify delays, bottlenecks, and inefficiencies in delivery operations, detect anomalies, and generate actionable recommendations for route optimization[cite: 5].

## 🛠 Methodology
* **Data Preprocessing & Feature Engineering:** Handled missing values, engineered datetime features, split geographic data, and aggregated trip and segment-level data[cite: 5].
* **Anomaly Detection & Outlier Treatment:** Identified operational anomalies representing delayed shipments and treated outliers using the Interquartile Range (IQR) method[cite: 5].
* **Hypothesis Testing:** Conducted paired t-tests to compare actual delivery times against estimated OSRM times[cite: 5].
* **Standardization:** Applied StandardScaler and MinMaxScaler for numerical normalization[cite: 5].

## 📊 Key Findings
* **Time Discrepancies:** Actual delivery times consistently and significantly exceed OSRM time predictions[cite: 5].
* **Transportation Modes:** FTL (Full Truck Load) routes demonstrate faster and more consistent deliveries, whereas Carting shows higher variability and is more affected by local delays[cite: 5].
* **Corridor Traffic:** High shipment density and frequent delays are heavily observed on major corridors connecting metro cities like Mumbai, Delhi, and Bengaluru[cite: 5].

## 💡 Recommendations
* **Route Estimation:** Improve route planning by integrating historical delay data rather than relying solely on OSRM estimates[cite: 5].
* **Fleet Planning:** Deploy more FTL vehicles on long-distance, high-volume routes and corridors with recurring overloads[cite: 5].
* **Carting Optimization:** Enhance short-distance carting operations through better route sequencing, delivery clustering, and dynamic vehicle assignment[cite: 5].
* **Warehouse Operations:** Address long waiting times by increasing staffing during peak hours, automating scanning, and introducing dock scheduling[cite: 5].

📄 **[Click here to view the full Jupyter Notebook/PDF](./Delhivery_business_case.pdf)**
