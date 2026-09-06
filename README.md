# 🚗 CarDekho Used Vehicle Exploratory Data Analysis (EDA)

An exploratory data analysis of used car and two-wheeler sales listings sourced from CarDekho. This project cleans, inspects, and analyzes pricing trends, fuel types, transmission preferences, vehicle usage, and dealership distribution using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Project Overview

Understanding the factors that influence used vehicle valuations is critical for buyers and dealerships alike. This repository contains end-to-end exploratory analysis examining:
- The statistical distributions of vehicle selling prices versus original ex-showroom prices.
- Market share across fuel types (Petrol, Diesel, CNG).
- Frequency and popularity of specific car makes and models.
- Vehicle usage patterns (kilometers driven and vehicle age).

---

## 📂 Dataset Overview

The dataset contains **301 vehicle entries** across **9 attributes** with zero missing values:

| Column Name | Type | Description |
| :--- | :--- | :--- |
| `Car_Name` | Categorical | Brand and model of the car or bike |
| `Year` | Numerical | Year of purchase / manufacture (ranging from 2003 to 2018) |
| `Selling_Price` | Numerical | Final sale price (in Lakhs ₹) |
| `Present_Price` | Numerical | Original ex-showroom price (in Lakhs ₹) |
| `Kms_Driven` | Numerical | Total distance the vehicle has run (km) |
| `Fuel_Type` | Categorical | Fuel system (`Petrol`, `Diesel`, `CNG`) |
| `Seller_Type` | Categorical | Channel of sale (`Dealer`, `Individual`) |
| `Transmission` | Categorical | Gearbox type (`Manual`, `Automatic`) |
| `Owner` | Numerical | Count of prior registered owners (0, 1, or 3) |

---

## 🔍 Key Data Insights

- **Data Quality:** Complete data integrity with **0 null/missing values** across all rows and columns.
- **Top Vehicle Models:** Out of 98 unique models, the most listed vehicles are:
  1. **Honda City:** 26 listings
  2. **Toyota Corolla Altis:** 16 listings
  3. **Hyundai Verna:** 14 listings
  4. **Toyota Fortuner:** 11 listings
  5. **Honda Brio:** 10 listings
- **Fuel Composition:**
  - **Petrol:** 239 vehicles (~79.4%)
  - **Diesel:** 60 vehicles (~19.9%)
  - **CNG:** 2 vehicles (~0.7%)
- **Pricing Trends:**
  - Average selling price: **₹4.66 Lakhs** (Median: **₹3.60 Lakhs**)
  - Range: **₹0.10 Lakhs** (budget two-wheelers) to **₹35.00 Lakhs** (luxury SUVs)
- **Vehicle Usage:**
  - Average kilometers driven: **~36,947 km** (Median: **32,000 km**)
  - Range: **500 km** to **500,000 km**
  - Average vehicle age: **~2013–2014 manufacturing year**

---

## 📊 Visualizations Included

1. **Model Distribution:** Horizontal count plot visualising the market volume of individual car models.
2. **Fuel Type Market Share:** Pie chart highlighting the dominance of petrol engines over diesel and alternative fuels.
3. **Fuel Type Frequency:** Bar plot showing category counts across fuel options.

---

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.8+
- **Libraries:**
  - `pandas` – Data loading, exploration, and aggregation
  - `numpy` – Numerical computation
  - `matplotlib` – Baseline figure and plot rendering
  - `seaborn` – Statistical distributions and categorical visualizations

---


