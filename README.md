# Week-1
AICTE Internship Cycle 2 - July 2025
# 🚗 EV Charging Demand Prediction — Week 1 Report

## 📌 Problem Statement
The growing adoption of Electric Vehicles (EVs) brings a critical need for efficient planning of charging infrastructure. This project aims to forecast EV adoption and charging demand by analyzing historical EV population data, vehicle types, and regional factors. 

### Objective:
> **To create a machine learning regression model that predicts future EV adoption and charging demand, enabling data-driven decisions for infrastructure development.**


## 🛠️ Tools & Technologies
- **Language**: Python 🐍
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Model**: Random Forest Regression
- **Platform**: Google Colab

# Week 2

## 📌 Problem Statement

As electric vehicle (EV) adoption continues to rise, urban planners and policymakers must anticipate infrastructure needs—particularly charging stations. Poor forecasting can lead to service bottlenecks, reduced user satisfaction, and setbacks to environmental and sustainability targets.

This project aims to **forecast future EV adoption** by building a **regression model** using historical vehicle registration data from Washington State. The outcome will help guide smarter investments in EV infrastructure such as charging stations.

---

## 🎯 Project Goal

- Develop a data-driven **regression model** to predict the number of electric vehicles (EVs) in future years.
- Use features such as:
  - Time-based trends (monthly vehicle registrations)
  - Regional distribution (by county)
  - Vehicle type (BEV, PHEV, non-EV)
  - Percent electric penetration
- Forecast future demand and support **urban EV infrastructure planning**.

---

## 📅 Dataset Overview

**Source:** [Kaggle – EV Population Size 2024](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024/data)

**Time Range:**  
`January 2017` to `February 2024`

**Features:**

| Feature | Description |
|--------|-------------|
| `Date` | Monthly snapshot of registrations (end of month) |
| `County` | Geographic region within Washington State |
| `State` | Address region (includes some out-of-state) |
| `Vehicle Primary Use` | Purpose of vehicle (Passenger: 83%, Truck: 17%) |
| `Battery Electric Vehicles (BEVs)` | Purely battery-powered EVs |
| `Plug-In Hybrid Electric Vehicles (PHEVs)` | Partially electric vehicles |
| `Electric Vehicle (EV) Total` | Sum of BEVs + PHEVs |
| `Non-Electric Vehicle Total` | Count of vehicles that are not EVs |
| `Total Vehicles` | All registered vehicles (EV + non-EV) |
| `Percent Electric Vehicles` | % of vehicles that are EVs in the region |

---

## 🛠️ Week 2 Progress

### ✅ Tasks Completed:
- Explored dataset and confirmed:
  - Time-series format is consistent
  - County-level granularity is available
- Identified key features for prediction
- Started preprocessing:
  - Handled missing values and outliers
  - Converted `Date` to datetime object
  - Created new time-based features: `Year`, `Month`, `Year-Month Index`
- Created visualizations to understand:
  - Yearly EV adoption trends
  - County-wise adoption differences
  - BEV vs PHEV composition over time

### 🔍 Initial Observations:
- **Steady upward trend** in EV adoption since 2017
- Certain counties are early adopters (e.g., King County, Snohomish)
- BEVs show faster growth than PHEVs
- Seasonal fluctuations in registration counts are minor but present

---

## 📦 Technologies & Tools

- **Languages:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, XGBoost
- **Environment:** Google Colab 
- **Data Source:** Kaggle dataset

---


