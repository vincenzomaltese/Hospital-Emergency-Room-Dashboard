# Hospital Emergency Room Dashboard

## 📌 Project Overview
This project is a **Power BI dashboard** designed to analyze and visualize key metrics related to emergency room (ER) operations in a hospital. The dataset includes patient demographics, wait times, department referrals, admission status, and satisfaction scores. The goal is to identify trends, optimize resource allocation, and improve patient care.

## 📂 Dataset Information
The dataset consists of patient records from **April 2023 to October 2024**, with **9,216 unique patients**. Below are the key columns included:

- `Patient ID`: Unique identifier for each patient
- `Admission Date`: Date of ER visit
- `Gender, Age, and Race`: Demographic details
- `Department Referral`: ER referral department (e.g., Orthopedics, Cardiology)
- `Admission Status`: Whether the patient was admitted or not
- `Wait Time`: Time elapsed before receiving medical attention
- `Satisfaction Score`: Patient's feedback on their ER experience

## 🎯 Business Objectives
1. Analyze patient demographics to understand trends in ER visits.
2. Evaluate wait times and their impact on patient satisfaction.
3. Identify peak hours and busy days for better staffing decisions.
4. Examine department referrals to optimize hospital resource allocation.
5. Compare admission rates and analyze patterns among admitted vs. non-admitted patients.

## 📊 Key Insights
- The **average wait time** was **35.3 minutes**, indicating room for efficiency improvements.
- The **patient satisfaction score** averaged **4.99/10**, highlighting areas for service enhancement.
- **Saturday** was the busiest day (**1,377 patients**), followed by **Thursday (1,332)** and **Sunday (1,318)**.
- **Peak hours** were from **11:00 PM to 08:00 AM**, requiring strategic staff deployment.
- **General Practice** and **Orthopedics** were the most common referrals among admitted patients.
- The racial composition showed **White (2,571), African American (1,951), Multiracial (1,557), and Asian (1,060)** as the predominant groups.

## 📌 Visualizations & Dashboard
The Power BI dashboard includes the following sections:
1. **Monthly View**: Breakdown of ER visits by month, patient demographics, and satisfaction scores.
![MonthlyView](https://github.com/vincenzomaltese/Hospital-Emergency-Room-Dashboard/blob/main/images/monthly_view.jpg)
2. **Consolidated View**: Aggregate statistics for a holistic view of the dataset.
![ConsolidatedView](https://github.com/vincenzomaltese/Hospital-Emergency-Room-Dashboard/blob/main/images/consolidated_view.jpg)
3. **Patient Details**: Individual patient records with key attributes.
![PatientDetails](https://github.com/vincenzomaltese/Hospital-Emergency-Room-Dashboard/blob/main/images/patient_details.jpg)
4. **Key Takeaways**: Summary of the most relevant insights for decision-making.
![KeyTakeaways](https://github.com/vincenzomaltese/Hospital-Emergency-Room-Dashboard/blob/main/images/key_takeaways.jpg)

## 🛠️ Tools & Technologies Used
- **Power BI**: Data visualization and dashboard creation
- **CSV Data Processing**: Importing and analyzing patient records
- **Power Query**: Data cleaning and preprocessing
- **DAX (Data Analysis Expressions)**: Created custom measures for:
  - **Average wait time**
  - **Bed occupancy rates**
  - **Patient influx trends**
  - **High-risk case identification**
- **Conditional Formatting**: Implemented visual indicators to highlight critical issues such as **overcrowding and increased wait times**.

## ⚠️ How to View the Dashboard
To fully interact with the Power BI dashboard, you need to have **Power BI Desktop** installed. If you do not have access to Power BI, you can refer to the **exported PDF version** of the dashboard for a static view of the insights.




