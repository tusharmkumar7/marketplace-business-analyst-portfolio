# Back Market — Marketplace Performance Analysis

## Business Data Analyst Portfolio Project

A complete end-to-end data analysis project simulating the work of a 
Business Data Analyst inside Back Market — a two-sided marketplace for 
refurbished electronics operating across Europe and North America.

---

## Project Overview

| Detail | Value |
|--------|-------|
| **Dataset** | 60 Sellers, 600 Orders, Jan 2023 – Dec 2025 |
| **Tools** | PostgreSQL, Excel, Power BI, PowerPoint |
| **Analyst** | Tushar Kumar |

---

## 5 Business Questions Answered

| # | Question | Tool |
|---|----------|------|
| Q1 | Which product categories generate the most revenue? | PostgreSQL + Excel |
| Q2 | Which customer countries drive the most orders and revenue? | PostgreSQL + Power BI |
| Q3 | Which sellers have the highest number of returned orders? | PostgreSQL + Excel |
| Q4 | Which product categories have the most returned orders? | PostgreSQL + Excel |
| Q5 | Which sellers had the highest completed order volume (2023–2025)? | PostgreSQL + Power BI |

---

## Key Findings

- **Laptops** lead total revenue at €71K despite fewer orders than Smartphones, 
  driven by a €676 avg order value — nearly 2× Smartphones
- **Belgium** is the #1 customer market by both orders (58) and revenue (€23.7K)
- **Spain** ranks 6th by orders but 3rd by revenue — highest avg order value (€380), 
  signalling a premium customer base
- **7 of the top 10 returning sellers** are Bronze tier with avg ratings below 4.0 — 
  a direct quality risk signal
- **Laptops carry a 24.7% return rate** — the highest of all categories despite 
  being the top revenue driver
- **Gold tier sellers** account for 51% of completed orders in the top 10

---

## Tools & Methodology

### PostgreSQL
- Built 2-table schema: `sellers` (60 rows) and `orders` (600 rows)
- Date range: January 2023 – December 2025
- Wrote 5 business queries using: SELECT, COUNT, SUM, LEFT JOIN, INNER JOIN, 
  WHERE, GROUP BY, ORDER BY, BETWEEN

### Excel
- Imported SQL query results into 5 structured worksheets
- Applied VLOOKUP, INDEX/MATCH, SUMIF, COUNTIF, RANK, IF formulas
- Used conditional formatting: data bars, color scales, highlight rules

### Power BI
- Built 4-page interactive dashboard
- Page 1: Revenue & Category Performance
- Page 2: Geographic Performance
- Page 3: Seller Quality & Returns
- Page 4: Top Seller Performance

### PowerPoint
- 10-slide executive presentation
- Structure: Business question → Data finding → Insight → Implication → Recommendation

---

## Repository Contents

| File | Description |
|------|-------------|
| `backmarket_portfolio_SQL.sql` | Full SQL schema and 5 business queries |
| `BackMarket_Portfolio_Excel.xlsx` | Excel workbook with 5 analysis sheets |
| `BackMarket_Portfolio.pptx` | 10-slide executive presentation |
| `/screenshots/` | Power BI dashboard screenshots |

---

## Data Schema

**sellers** — 60 rows
