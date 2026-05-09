# 📊 Micro Spending Analysis using Exploratory Data Analysis (EDA)

## 🚀 Project Overview
This project performs an in-depth **Exploratory Data Analysis (EDA)** on daily micro spending data to uncover hidden patterns, trends, and behavioral insights.  

The focus is on identifying **frequent low-value transactions (< ₹100)** that often go unnoticed but significantly impact overall expenses over time.

---

## 🎯 Objectives
- Analyze daily spending behavior over a 30-day period  
- Identify high-frequency micro transactions  
- Understand category-wise expense distribution  
- Evaluate preferred payment methods  
- Generate actionable financial insights  

---

## 📂 Dataset Information
The dataset consists of structured transaction records with the following features:

| Column Name     | Description                          |
|----------------|--------------------------------------|
| Date           | Transaction date                     |
| Category       | Expense type (Food, Transport, Online) |
| Amount         | Transaction value (₹)                |
| Payment_Mode   | Payment method (UPI, Cash, Card)     |
| Location       | Place of transaction                 |

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Development environment  

---

## 🔍 Exploratory Data Analysis

### ✔ Data Cleaning
- Removed duplicate records  
- Checked for missing values  
- Converted date column into datetime format  

### ✔ Feature Engineering
- Extracted day-wise insights from date  
- Grouped data for trend analysis  

---

## 📊 Key Visualizations

> *(Add your screenshots in an `images/` folder and update paths below)*

### 📌 Category-wise Spending
![Category Spending](images/category_spending.png)

### 📌 Daily Spending Trend
![Daily Trend](images/daily_trend.png)

### 📌 Payment Mode Usage
![Payment Mode](images/payment_mode.png)

### 📌 Amount Distribution
![Distribution](images/distribution.png)

### 📌 Correlation Heatmap
![Heatmap](images/heatmap.png)

---

## 📊 Key Visualizations

### Category-wise Spending
![Category](category_spending.png)

### Daily Spending Trend
![Trend](daily_trend.png)

### Distribution
![Distribution](distribution.png)

### Heatmap
![Heatmap](heatmap.png)

---

## 💡 Key Insights

- 🥗 **Food category dominates overall spending**, indicating frequent daily purchases  
- 💸 A significant number of transactions are **below ₹100**, confirming micro spending behavior  
- 📱 **UPI is the most preferred payment method**, reflecting digital adoption  
- 📈 Spending shows **daily fluctuations with noticeable peaks**  
- 🔁 Small repeated expenses accumulate into a **considerable total over time**  

---

## 📈 Conclusion
This analysis highlights the importance of tracking micro expenses. While individual transactions may seem insignificant, their cumulative effect plays a major role in overall financial health.  

Understanding these patterns can help in making **better budgeting and spending decisions**.

---

## 🚀 Future Enhancements
- Build an interactive dashboard using **Power BI / Tableau**  
- Implement **predictive models** for expense forecasting  
- Expand dataset for long-term behavioral analysis  

---

## 📁 Project Structure
