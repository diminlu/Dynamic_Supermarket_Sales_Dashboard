# Dynamic Supermarket Sales Dashboard

An interactive Excel dashboard analyzing two years of supermarket transactions, 527 orders spanning January 2021 through December 2022. Built with PivotTables, PivotCharts, and slicers to explore revenue, profit margin, product performance, and sales channel mix, no plugins, no external BI tools, just Excel used to its full potential.

![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot%20Tables-blue?style=flat)
![Dashboard](https://img.shields.io/badge/Type-Interactive%20Dashboard-informational?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-success?style=flat)

<img width="2482" height="1395" alt="image" src="https://github.com/user-attachments/assets/bd403e74-b409-47da-bc42-167c938dc333" />

---

## Table of Contents

- [Overview](#overview)
- [Key Metrics](#key-metrics)
- [Key Findings](#key-findings)
- [Dashboard Breakdown](#dashboard-breakdown)
- [How It Works](#how-it-works)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Repository Contents](#repository-contents)
- [Why This Project](#why-this-project)

---

## Overview

This project turns two years of raw supermarket transaction data into a fully interactive Excel dashboard, built for retail managers and executives who need a fast, consolidated read on business performance without opening a BI tool. Every visualization is filterable through slicers, so a stakeholder can drill into a specific product, category, sale type, or payment mode without needing a rebuild for every question.

---

## Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | $401,411.92 |
| Total Cost | $332,504.00 |
| Total Profit | $68,907.92 |
| Overall Profit Margin | 17.2% |
| Total Orders | 527 |
| Date Range | Jan 2021 – Dec 2022 |

---

## Key Findings

### Revenue & Profit
- Revenue grew from **$187,284** in 2021 to **$214,128** in 2022, a year-over-year increase of roughly 14%
- Profit followed the same trend, rising from **$30,315** in 2021 to **$38,593** in 2022

### Category Performance
- Category04, Category02, and Category05 are the top three revenue-generating categories, each bringing in over $90,000
- Category02 carries the highest profit margin at **18.9%**, narrowly ahead of Category04 (18.5%) and Category05 (18.2%)
- Category01 and Category03 trail both on revenue and margin, with Category03 the lowest at 13.6%

### Product Performance
- Product41 and Product30 are the top two products by revenue, each generating roughly $23,000
- The lowest-performing products (Product09, Product25, Product35) each generated under $2,000 in total revenue across the two-year period

### Sales Channel Mix
- Direct Sales is the dominant channel, accounting for **51.9%** of revenue
- Online sales contribute **33.4%**, and Wholesaler orders make up the remaining **14.8%**

### Payment Preferences
- Payment method is almost evenly split: **50.3%** of revenue comes through Online payment, **49.7%** through Cash

---

## Dashboard Breakdown

**Revenue & Profitability**
- Total Revenue, Total Cost, Total Profit, and Profit % as headline KPIs
- Monthly sales and profit trend view

**Category & Product Performance**
- Revenue and profit margin by category
- Product-level revenue and quantity sold, sortable to surface top and bottom performers

**Sales Channel Mix**
- Revenue breakdown by Sale Type (Direct Sales, Online, Wholesaler)

**Payment Behavior**
- Revenue split by Payment Mode (Cash vs. Online)

**Filterable Dimensions**
- Slicers connected across every visual, filtering by category, product, sale type, payment mode, month, or year updates the entire dashboard at once

---

## How It Works

1. Open `Supermarket_Sales_Dashboard.xlsx`
2. Use the slicers to filter by category, product, sale type, payment mode, or date
3. Every PivotChart and KPI on the dashboard recalculates instantly based on the current filter selection
4. Reference `Raw_Data.xlsx` for the underlying two years of transaction records the dashboard is built from

---

## Built With

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Native formulas (no third-party add-ons)

---

## Getting Started

1. Download `Supermarket_Sales_Dashboard.xlsx` from this repository
2. Open it in Excel
3. Use the slicers on the dashboard to filter and explore the data
4. Reference `Raw_Data.xlsx` if you want to inspect or reuse the underlying transaction data

---

## Repository Contents

| File | Description |
|---|---|
| `Supermarket_Sales_Dashboard.xlsx` | The interactive dashboard, built with PivotTables, PivotCharts, and slicers |
| `Raw_Data.xlsx` | The underlying two years of supermarket transaction data (527 orders, Jan 2021–Dec 2022) |
