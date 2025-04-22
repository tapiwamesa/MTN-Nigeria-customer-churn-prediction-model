## About Dataset
MTN Nigeria Customer Churn & Usage Dataset (2025)

## 🧠 Context
Customer churn is one of the biggest concerns for telecom companies, especially in competitive markets like Nigeria. This dataset simulates the behavior, preferences, and churn patterns of MTN Nigeria customers in Q1 2025. It provides rich insight into device usage, data plan preferences, age groups, tenure, churn drivers, and revenue patterns.

## 📌 Inspiration & Purpose
The dataset was inspired by real-world customer behavior and is designed to enable:

# Exploratory Data Analysis (EDA)
1. Churn prediction modeling
2. Customer segmentation
3. Dashboard development
4. Data storytelling
5. Telecom business strategy analysis

Whether its data science, building dashboards in Excel or Power BI, or testing machine learning models, this dataset is designed to feel real—and give you meaningful insights.

## 🔍 Data Sources
- MTN Nigeria eShop (https://shop.mtn.ng/):
- All device types, data plan names, and pricing were taken directly from the official MTN eShop in Q1 2025.
- All customer records and usage patterns were synthetically generated for educational and analytical purposes with the assistance of ChatGPT (OpenAI).

## 🧾 Dataset Structure
This dataset contains 974 rows of customer entries and the following columns:

- **Customer ID**: A unique identifier assigned to each customer. May appear more than once if the customer owns multiple devices.
- **Full Name**: The full name of the customer. Names reflect a balance across Nigerian ethnicities and regions.
- **Date of Purchase**: Month and year the device or plan was purchased. All entries are from 2025.
- **Age**: Age of the customer (between 16 and 80). Rules apply to age and purchasing behavior.
- **State**: Nigerian state where the customer resides, including the FCT.
- **MTN Device**: Device purchased by the customer. Includes: Mobile SIM Card, Broadband MiFi, 4G Router, 5G Broadband Router.
- **Gender**: Gender of the customer (Male or Female).
- **Satisfaction Rate**: A score from 0 to 5 reflecting the customer’s satisfaction.
- **Customer Review**: Categorical review of the customer experience: Poor, Fair, Good, Very Good, Excellent.
- **Customer Tenure in months**: How long the customer has been subscribed (in months).
- **Subscription Plan**: The name of the MTN data plan purchased (e.g., 60GB Monthly Broadband Plan, 7GB Monthly Plan, etc.).
- **Unit Price**: Cost of the data plan in Nigerian Naira (₦).
- **Data Usage**: Estimated data usage in gigabytes (GB). Not necessarily equal to the plan size—it reflects usage behavior.
- **Number of Times Purchased**: How many times the plan was purchased within the month (simulates customer consumption rate).
- **Total Revenue**: Total amount spent by the customer (calculated as Unit Price × Number of Times Purchased).
- **Customer Churn Status**: Indicates whether the customer has churned (Yes) or is still active (No).
- **Reasons for Churn**: If churned, this field shows the reason (e.g., Poor Network, Relocation, High Call Tariffs, etc.). Empty for active customers.

## ✅ Why Use This Dataset
- Practice data wrangling, grouping, and pivoting
- Build Excel, Tableau, or Power BI dashboards
- Train classification models (e.g., churn prediction)
- Perform market segmentation
- Develop telecom customer personas
- Explore synthetic data that feels real but respects privacy

## 💡 Credit & Collaboration
- Data Creator: Oluwademilade Adeniyi
- Assisted by ChatGPT by OpenAI
- Based on: Official MTN Nigeria product and pricing data from the MTN eShop.
