# Customer-Churn-Analysis-Python
“Customer churn analysis using Python &amp; Google Colab – data cleaning, EDA, visualization, insights, and business recommendations.”
📌 Project Overview

This project analyzes telecom customer churn using Python in Google Colab.
The goal is to understand why customers leave, which customer segments are at risk, and what business factors drive churn.

The dataset contains demographic details, subscription information, billing patterns, and churn labels.

📂 Files Included
File	Description
Customer_Churn_Analysis.ipynb	Google Colab notebook with complete Python code
Customer_Churn.csv	Dataset used for analysis
README.md	Documentation


🔗 Open in Google Colab

<a href="https://colab.research.google.com/drive/1RUJQiU5tTHxneprklbVH6AtDgJkVOXiC" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
</a>





🧾 Dataset Details
Demographics

CustomerID

Gender

SeniorCitizen

Partner

Dependents

Subscription Details

PhoneService

InternetService

OnlineSecurity

TechSupport

DeviceProtection

StreamingTV

StreamingMovies

Account & Billing

Contract

PaperlessBilling

PaymentMethod

MonthlyCharges

TotalCharges

Tenure

Target

Churn → Yes / No

🛠 Technologies Used

Python

Pandas
– Numpy
– Matplotlib
– Seaborn
– Google Colab

📊 Analysis Performed
✔ 1. Data Cleaning

Missing values handled

Incorrect data types fixed

Extra spaces removed

Converted TotalCharges to numeric

✔ 2. Exploratory Data Analysis

Created visualizations for:

Gender vs Churn

Tenure vs Churn

Contract type vs Churn

Senior Citizens vs Churn

Monthly charges comparison

Payment method patterns

Internet service impact

Security/Tech Support impact

✔ 3. Visualizations

Histograms

Count plots

Bar charts

Boxplots

Heatmaps

🎯 Key Insights
🔹 1. Low-tenure customers churn most

Churn is very high in the first 0–6 months.

🔹 2. Month-to-month contract → highest churn

Annual & two-year contracts show lower churn.

🔹 3. Customer with no tech support/security churn more

Important to sell protection packages.

🔹 4. Fiber optic users churn more

May indicate service or cost dissatisfaction.

🔹 5. High monthly charges → high churn

Customers paying $80+ churn the most.

🔹 6. Senior citizens show higher churn
🔹 7. Electronic check users churn the most
🚀 Business Recommendations

✔ Offer onboarding support in the first 90 days
✔ Give discounts for annual contracts
✔ Bundle tech support & security services
✔ Review pricing for high-charge customers
✔ Improve fiber optic customer satisfaction
✔ Create a senior citizen support program

▶ How to Run

Clone/download repository

Open notebook in Colab

Upload CSV

Run all cells

🙋 Author – Vishal Sharma
