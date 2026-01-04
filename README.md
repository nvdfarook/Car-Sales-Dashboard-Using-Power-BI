# 🚗 Car Sales Dashboard – Power BI Project

## 📊 Project Overview
This project is an **interactive Car Sales Dashboard** built using **Microsoft Power BI**, designed to analyze and visualize car sales performance across multiple dimensions such as time, body style, color, dealer region, and company.

The dashboard helps stakeholders quickly understand **Year-to-Date (YTD)** and **Month-to-Date (MTD)** performance, identify trends, and drill down into detailed transaction-level data.

---
<img width="1349" height="750" alt="Screenshot (207)" src="https://github.com/user-attachments/assets/5c48a2c8-2d3f-40f1-bf64-f36ccd5720b8" />

<img width="1329" height="749" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/882fcecf-d6af-4781-8d34-da3c77b4c3dc" />

---

## 🎯 Objectives
- Analyze **overall car sales performance**
- Track **YTD and MTD sales, average sales, and units sold**
- Identify **top-performing car companies and models**
- Understand sales distribution by **body style, color, and region**
- Enable **detailed drill-down analysis** for individual sales records

---

## 🛠 Tools & Technologies Used
- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Modeling**
- **Interactive Visualizations**

---

## 📌 Dashboard Pages

### 🏠 1. Home (Overview Page)
This page provides a **high-level summary** of car sales performance.

#### 🔹 Key KPIs
- **YTD Sales**
- **MTD Sales**
- **YTD Average Sales**
- **MTD Average Sales**
- **YTD Cars Sold**
- **MTD Cars Sold**
- **Growth % (Year-over-Year)**

#### 🔹 Visuals Included
- 📈 **YTD Price by Week** (Line Chart)
- 🍩 **YTD Sales by Body Style** (Donut Chart)
- 🍩 **YTD Sales by Color** (Donut Chart)
- 🗺 **YTD Sales by Dealer Region** (Map Visual)
- 📋 **Company-wise Performance Table**
  - YTD Avg Sale
  - YTD Cars Sold
  - YTD Sales
  - % Contribution to Total Sales

---

### 📄 2. Details Page
This page allows **transaction-level analysis** with full visibility into individual sales records.

#### 🔹 Detailed Table Fields
- Car ID
- Date
- Customer Name
- Dealer Name
- Company
- Model
- Color
- Total Sale Amount

This page is useful for:
- Auditing data
- Verifying transactions
- Deep-dive analysis

---

## 🎛 Filters & Slicers
The dashboard includes interactive slicers for:
- **Body Style**
- **Dealer Name**
- **Engine Type**
- **Transmission**

These slicers dynamically update all visuals across the page.

---

## 🧠 DAX Measures Used (Examples)
- `YTD Sales`
- `MTD Sales`
- `YTD Avg Sales`
- `MTD Avg Sales`
- `YTD Cars Sold`
- `% Growth`
- `% Contribution to Total Sales`

Advanced DAX concepts such as:
- `TOTALYTD`
- `TOTALMTD`
- `CALCULATE`
- `FILTER`
- `ALL / ALLSELECTED`
were used for accurate time-based calculations.

---

## 📈 Key Insights
- SUVs and Sedans contribute significantly to total sales
- Certain colors dominate customer preferences
- Regional analysis highlights top-performing dealer locations
- A small number of companies contribute a large share of total revenue

---

## 📷 Dashboard Preview
> Screenshots of the **Overview** and **Details** pages are included in this repository for reference.

---

## 🚀 How to Use
1. Download the `.pbix` file from the repository
2. Open it using **Power BI Desktop**
3. Refresh the data (if required)
4. Interact with slicers and visuals for insights

---


