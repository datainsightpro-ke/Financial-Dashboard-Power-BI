# Financial Dashboard – Power BI Project

## 📊 Project Overview
This project is an **interactive Financial Dashboard developed using Microsoft Power BI**.  
It focuses on transforming raw financial transaction data into actionable insights through **data modeling, Power Query transformations, DAX measures, and interactive visualizations**.

The dashboard is designed for **financial reporting, performance monitoring, and portfolio demonstration**.

---

## 🎯 Project Objectives
- Analyze **Income vs Expenses**
- Track spending by **category**
- Compare financial performance across **regions**
- Analyze payment methods usage
- Identify **monthly financial trends**
- Provide an interactive, user-friendly reporting dashboard

---

## 🗂 Dataset Description
The dataset consists of structured financial transaction records with the following key fields:

- **Date** – Transaction date  
- **Transaction ID** – Unique transaction identifier  
- **Account Type** – Income, Expense, Asset, or Liability  
- **Category** – Rent, Sales, Marketing, Equipment, etc.  
- **Amount** – Transaction value  
- **Transaction Type** – Income or Expense  
- **Payment Method** – Cash, Credit Card, Bank Transfer  
- **Region** – North, South, East, West  
- **Month / Year** – Used for trend analysis  

---

## ⚙️ Tools & Technologies Used
- Microsoft Power BI
- Power Query (ETL)
- DAX (Data Analysis Expressions)
- Data modeling & relationships
- Interactive visuals & slicers

---

## 📈 Dashboard Features
- **Total Income, Total Expenses, and Net Balance KPIs**
- Expense breakdown by **Category**
- Financial performance by **Region**
- Distribution by **Payment Method**
- **Monthly income and expense trends**
- Interactive filters for:
  - Region
  - Category
  - Payment Method
  - Date

---

## 🧠 Key Insights Generated
- Identifies highest spending categories
- Highlights regions with the largest expenses
- Compares income vs expenses clearly
- Tracks financial performance over time
- Supports data-driven financial decisions

---

## 🧾 Code Notes (Important)
This project uses **Power BI logic instead of traditional programming languages**.

### Power Query (ETL)
- Data cleaning and transformation
- Column renaming and type formatting
- Handling missing or inconsistent values
- Creating derived columns for analysis

### Data Modeling
- Logical relationships between tables
- Optimized model for reporting performance

### DAX Measures
Examples of calculations implemented using DAX:
- Total Income
- Total Expenses
- Net Balance (Income – Expenses)
- Monthly aggregations
- Category and region-based measures

> 📌 Note:  
> No external scripts (Python/R) were used.  
> All transformations and calculations were implemented using **Power BI native features**.

---

## 📁 File Structure
power BI dashboard 001.pbix
│
├── Power Query
│ └── Data cleaning and transformation steps
│
├── Data Model
│ └── Relationships and calculated measures
│
└── Dashboard
└── Interactive visuals, KPIs, and slicers
