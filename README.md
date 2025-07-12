# 📊 UPI Transactions Power BI Dashboard

## 📁 Overview
This Power BI dashboard visualizes and analyzes UPI transaction data to uncover trends, user behavior, and payment patterns. It includes interactive slicers, dynamic bookmarks, custom DAX logic, and multiple synced pages for seamless analysis.

---

## ⚙️ What This Project Includes

- **Data Cleaning & Transformation**  
  Loaded Excel data, renamed sheets, split transaction time, and ensured correct data types for account numbers.

- **Data Profiling**  
  Enabled Power BI’s column profiling tools to verify data quality and confirm there were no nulls, duplicates, or errors.

- **Interactive Slicers**  
  Designed and formatted slicers for fields like Bank Name, Gender, City, and Device Type. Slicers were synced across all report pages for a consistent experience.

- **Custom Age Grouping**  
  Created a DAX-based `Age Groups` column to segment users into A1 (≤25), A2 (26–35), and A3 (>35) for targeted demographic analysis.

- **Visualizations**  
  Developed interactive visuals across two report pages:
  - Line Chart (Amount vs Transaction Date)
  - Matrix Visual with conditional formatting
  - Filters for Currency and Transaction Type

- **Bookmark Navigation**  
  Implemented bookmarks and buttons to toggle between visual types (Line Chart vs Column Chart), and between metrics (`Amount` vs `Remaining Balance`).

---

## 📌 Key Features

- Time-series analysis of UPI transaction amounts
- Age-based demographic segmentation
- Device-wise and bank-wise transaction breakdown
- Conditional formatting in matrix visuals
- Bookmark buttons to switch between chart types
- Synchronized slicers across all report pages

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Use the slicers, filters, and bookmark buttons to interact with the dashboard.

---


