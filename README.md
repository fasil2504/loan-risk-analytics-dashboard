# 🏦 Banking Risk Analytics Dashboard

## 📌 Project Overview
This project focuses on exploring banking data to assist financial institutions in making smarter loan decisions. By analyzing customer behavior, engagement patterns, and risk profiles, we created an interactive dashboard that helps identify whether a loan applicant is likely to repay the loan or not.

---

## 🎯 Problem Statement
Develop a basic understanding of risk analytics in the banking and financial services sector. Use data to **minimize lending risks** by evaluating client data during the loan approval process.

---

## 💡 Solution
Using a combination of **Python**, **MySQL**, and **Power BI**, we:
- Cleaned and transformed raw banking data
- Structured it using relational modeling in MySQL
- Visualized it in Power BI to enable decision-making based on client risk profiles

---

## 🧰 Tools & Technologies
- **Python** – Data cleaning and preprocessing (Pandas, NumPy)
- **MySQL** – Data storage and relational queries
- **Power BI** – Dashboard development and interactive reporting

---

## 🗂 Dataset Description
The dataset contains multiple interconnected tables:
- `Banking_Relationship`
- `Client_Banking`
- `Gender`
- `Investment_Advisor`
- `Period`

Relationships are defined using **primary and foreign keys** to ensure normalization and efficiency.

---

## 🧹 Data Cleaning Highlights
- Removed null values and duplicates
- Created a new column: `Engagement Timeframe` in the `Client_Banking` table to track client-bank duration
- Standardized date formats and data types
- Loaded cleaned data into **MySQL**

---

## 📊 Power BI Dashboard Features
- **Client Risk Analysis**: Profile-based loan risk prediction
- **Timeframe Tracking**: Length of engagement insights
- **Advisor & Gender Analysis**: Trends by client categories
- **Interactive Filters**: Drill-down by relationship period, advisor, or demographics

---


## 🖥 Dashboard Preview

Here’s a snapshot of the Power BI dashboard:

<p align="center">
  <img src="images/Banking Dasbord Home_01.png" alt="Power BI Banking Dashboard" width="700"/>
</p>

Additional drill-downs and interactive filters allow stakeholders to explore detailed client risk segments, branch performance, and advisor trends.

---

## 🔍 Key Insights
- High-risk clients often show shorter engagement periods
- Certain client segments show consistently better repayment behavior
- Advisor assignments correlate with loan performance patterns

---

## ✅ Outcome
- A dynamic and actionable dashboard for banking decision-makers
- Data-driven support for approving or rejecting loan applications
- Enhanced visibility into client-bank relationships

---

## 📎 How to Use
1. Clone this repo
2. Use the Python scripts to process and clean raw data
3. Import the cleaned data into your MySQL server
4. Open the `.pbix` file in Power BI to explore the dashboard

---

## 📁 Repository Structure
