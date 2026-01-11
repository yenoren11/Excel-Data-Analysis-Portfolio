# Bike Sales Customer Analysis Project (Excel)

## 📌 Project Overview
This project focuses on cleaning and analyzing a dataset of customer demographics to identify the key factors that influence the decision to purchase a bike. The final goal is to build an interactive dashboard that provides actionable insights for marketing strategies.

## 🛠 Data Workflow & Methodology

### 1. Data Cleaning - Sheet: `Working Sheet`
The raw data underwent a rigorous cleaning process to ensure accuracy and consistency:
* **Remove Duplicates:** Identified and removed duplicate records based on Customer ID to ensure data integrity.
* **Data Standardization:**
    * `Marital Status` column: Replaced abbreviations `M` with `Married` and `S` with `Single`.
    * `Gender` column: Replaced abbreviations `M` with `Male` and `F` with `Female`.
* **Data Formatting:** Converted the `Income` column to **Currency** format.
* **Data Transformation (Age Brackets):** Created a new column named `Age Brackets` using nested `IF` statements to categorize customers:
    * **Adolescent:** Age < 31.
    * **Middle Age:** Age >= 31 and Age <= 54.
    * **Old:** Age > 54.


### 2. Data Analysis - Sheet: `Pivot Table`
Utilized Pivot Tables to summarize and aggregate key metrics:
* Average income per purchase filtered by gender.
* Count of bike purchases based on customer commute distance.
* Customer purchase distribution across different age brackets.

### 3. Interactive Dashboard
Designed a professional dashboard with dynamic visualizations and **Slicers**, allowing users to filter data by:
* Marital Status
* Region
* Education Level

> *Dashboard Preview:*
![Dashboard Preview](Project-1-Bike-Sale/Images/dashboard_preview.png)

## 📊 Key Insights
* **Demographics:** Customers in the **Middle Age** group (31-54) are the primary buyers of bikes.
* **Income Factor:** On average, individuals who purchased a bike have a higher income level compared to those who did not.
* **Commute Distance:** Customers with a short commute (0-1 miles) show the highest conversion rate.

---
*This project was completed as part of the Excel Data Analyst tutorial by Alex The Analyst.*
