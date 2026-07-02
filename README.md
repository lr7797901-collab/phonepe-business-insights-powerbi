# 📱 PhonePe Business Insights Dashboard | Power BI

> An end-to-end Power BI project that transforms raw PhonePe transaction data into interactive dashboards, enabling business insights through KPI tracking, DAX calculations, data modeling, and visualization.

---

# 📌 Project Overview

This project analyzes PhonePe digital payment transactions and user data using Power BI. It demonstrates the complete Business Intelligence workflow, including data cleaning, data modeling, DAX calculations, KPI development, and interactive dashboard design to support data-driven decision-making.

---

# 🎯 Project Objectives

- Analyze PhonePe transaction performance.
- Monitor transaction value and transaction volume.
- Track registered users and user engagement.
- Measure payment success rate.
- Perform Month-over-Month (MoM) analysis.
- Build interactive dashboards for business insights.

---

# 🛠️ Tech Stack

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Modeling
- Git & GitHub

---

# 📂 Dataset

The dataset used in this project is included in this repository.

Dataset File:

- 📄 [Phonepe-Final-Dataset.xlsx](Phonepe-Final-Dataset.xlsx)

The dataset contains two worksheets:

- **All_Transactions** – Transaction details including Transaction ID, Amount, Date, Payment Status, Service Type, Service, Reason, and User ID.
- **All_Users** – User information including User ID, Name, Age, Age Segment, and Join Date.

These datasets are used to build relationships, create DAX measures, and generate interactive dashboards.

---

# 📊 Executive Dashboard

The Executive Dashboard provides a comprehensive overview of business performance through key KPIs such as Total Transaction Value, Total Transactions, Registered Users, Success Rate, and Month-over-Month Growth. Interactive filters enable users to explore business performance across different periods.

![Executive Dashboard](executive-dashboard.png)

---

# 🧮 DAX Measures

Custom DAX measures were created to calculate KPIs such as Total Transactions, Transaction Value, Success Rate, Previous Month Metrics, and Month-over-Month Growth.

![DAX Measures](dax-measures.png)

---

# 🗂️ Data Model & Relationships

The project follows a **Star Schema** data model with **All_Transactions** as the fact table and **All_Users** and **Date_Table** as dimension tables. Relationships based on **User_ID** and **Date** enable efficient filtering, time intelligence, and dynamic business analysis.

![Data Model](data-model-relationships.png)

---

# 📂 Power BI Report

The original **PhonePe_Business_Insights.pbix** file is included in this repository, allowing users to explore the complete interactive dashboard, review the data model, inspect DAX measures, and understand the end-to-end Power BI development process.

---

# 📈 Key Performance Indicators (KPIs)

- Total Transaction Value
- Total Transactions
- Total Registered Users
- Successful Transactions
- Success Rate
- Previous Month Transaction Value
- Previous Month Transactions
- Month-over-Month Transaction Growth
- Month-over-Month Transaction Value Growth

---

# 💡 Business Insights

- Analyzed transaction trends using interactive dashboards.
- Evaluated payment success rate through custom DAX calculations.
- Compared Month-over-Month business performance.
- Built KPIs for monitoring business growth.
- Designed dashboards to support data-driven decision-making.

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Power Query (ETL)
- Data Modeling
- Star Schema Design
- DAX Calculations
- KPI Development
- Dashboard Design
- Business Intelligence
- Data Visualization
- Time Intelligence
- Business Storytelling

---

# 📁 Repository Contents

```
📦 phonepe-business-insights-powerbi
│── README.md
│── PhonePe_Business_Insights.pbix
│── Phonepe-Final-Dataset.xlsx
│── executive-dashboard.png
│── dax-measures.png
│── data-model-relationships.png
```

---

# 👨‍💻 Author

**Laxman Ram**

🎓 B.Tech, NIT Raipur

📊 Aspiring Data Analyst

🔗 LinkedIn: https://linkedin.com/in/laxmanram81

🔗 GitHub: https://github.com/lr7797901-collab

---

⭐ If you found this project helpful, consider giving it a **Star**.
