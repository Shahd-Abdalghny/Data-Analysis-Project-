# 📊 Vodafone Telecommunications Analytics Dashboard
<img width="1380" height="732" alt="image" src="https://github.com/user-attachments/assets/b00aeb99-c7d9-4261-9986-22fadb8b24e2" />

A Business Intelligence project that analyzes Vodafone telecommunications data using **Python** for data cleaning and **Power BI** for interactive dashboard visualization.

---

# 📌 Project Overview

The goal of this project is to transform raw telecommunications data into meaningful business insights that support decision-making.

The project covers customer analysis, subscriptions, recharge behavior, shop sales, and customer complaints.

---

# 🎯 Objectives

- Analyze customer demographics.
- Monitor subscription trends.
- Analyze recharge transactions.
- Evaluate shop sales performance.
- Monitor customer complaints.
- Build an interactive Power BI dashboard.
- Generate business insights and recommendations.

---

# 📂 Dataset

The project consists of five related datasets:

| Dataset | Description |
|---------|-------------|
| Subscribers | Customer information |
| Subscriptions | Subscription details |
| Recharges | Recharge transactions |
| Shop Sales | Vodafone retail sales |
| Complaints | Customer complaints |

---

# 🧹 Data Cleaning

The data was cleaned using Python (Pandas).

Cleaning steps included:

- Removing duplicates
- Handling missing values
- Standardizing governorate names
- Splitting Region and ZIP Code
- Converting date columns
- Converting monetary values to numeric
- Removing invalid values
- Correcting inconsistent text formatting

---

# 🗂 Data Model

The Power BI model includes relationships between all datasets.

Main Keys:

- subscriber_id
- subscription_id

A Calendar table was created to support time-based analysis.

---

# 📈 Dashboard Pages

## 🏠 Home

Provides an executive overview using KPIs and navigation buttons.

KPIs include:

- Total Subscribers
- Total Revenue
- Total Shop Sales
- Total Complaints
- Average Satisfaction
- Average Resolution Days

---

## 👥 Subscribers Dashboard

- Total Subscribers
- Gender Distribution
- Age Distribution
- Customer Segments
- Subscribers by Governorate

---

## 📱 Subscriptions Dashboard

- Total Subscriptions
- Line Type Distribution
- Subscription Trend
- Phone Number Analysis

---

## 💳 Recharges Dashboard

- Total Revenue
- Total Transactions
- Average Recharge
- Revenue Over Time
- Revenue by Payment Method
- Recharge Amount Distribution

---

## 🛒 Shop Sales Dashboard

- Total Sales
- Quantity Sold
- Average Order Value
- Sales by Branch
- Top Selling Products
- Revenue by Product Category

---

## 📞 Complaints Dashboard

- Total Complaints
- Complaints by Category
- Average Resolution Days
- Satisfaction Score Distribution
- Resolution Days vs Satisfaction
- Complaints Trend

---

# 💡 Business Insights

Examples of insights generated from the dashboard:

- Identify the governorates with the highest number of subscribers.
- Compare recharge performance over time.
- Analyze customer payment preferences.
- Identify top-selling products.
- Discover the most common complaint categories.
- Evaluate customer satisfaction.
- Compare branch performance.

---

# 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Power BI
- DAX
- Microsoft Excel

---

# 📊 Power BI Features

- Interactive Dashboard
- KPIs
- Drill-down Analysis
- Slicers
- Navigation Buttons
- Dynamic Filtering
- Time Intelligence
- Data Modeling

---

# 📁 Project Structure

```
Vodafone-Telecommunications-Dashboard/
│
├── data/
│   ├── subscribers_clean.csv
│   ├── subscriptions_clean.csv
│   ├── recharges_clean.csv
│   ├── shop_sales_clean.csv
│   └── complaints_clean.csv
│
├── notebooks/
│   └── Data_Cleaning.ipynb
│
├── powerbi/
│   └── Vodafone_Dashboard.pbix
│
├── images/
│   ├── home.png
│   ├── subscribers.png
│   ├── subscriptions.png
│   ├── recharges.png
│   ├── shop_sales.png
│   └── complaints.png
│
└── README.md
```

---

# 🚀 Future Improvements

- Real-time dashboard
- Predictive analytics using Machine Learning
- Customer churn prediction
- Sales forecasting
- Complaint prediction

---

# 📷 Dashboard Preview

*(Add screenshots of your Power BI pages here.)*

Example:

```
Home Dashboard
```

(Add image)

```
Subscribers Dashboard
```

(Add image)

---

# 📬 Contact

**Name:** Shahd Abdelghany

Faculty of Computers and Information

South Valley University

GitHub: *(Your GitHub Profile)*

LinkedIn: *(Your LinkedIn Profile)*

---

# ⭐ If you like this project, don't forget to give it a Star.
