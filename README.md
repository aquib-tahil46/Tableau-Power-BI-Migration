# 🔄 Tableau → Power BI Migration
The objective was to migrate a Wealth Management MIS from **Excel → Tableau → Power BI** while preserving business logic, KPI definitions, executive reporting standards, and decision-making workflows.

## Why this Migration?

This repository demonstrates an **enterprise BI migration**, not simply another Power BI dashboard.

The objective was to migrate a Wealth Management MIS from **Excel → Tableau → Power BI** while preserving business logic, KPI definitions, executive reporting standards, and decision-making workflows.

Instead of redesigning reports from scratch, the entire analytical solution was rebuilt using Power BI's semantic model, DAX, Power Query, and Row-Level Security.

---

## Migration Journey

```
Excel MIS
     │
     ▼
SQL Data Cleaning
     │
     ▼
Tableau Executive Dashboard
     │
     ▼
Business KPI Validation
     │
     ▼
Power BI Migration
     │
     ▼
Star Schema + DAX + Power Query + RLS
     │
     ▼
Executive Dashboard

---

## Executive Dashboard (Power BI)

<img src="https://github.com/user-attachments/assets/9b6d840d-cba9-4a77-8ab0-041cab93c594">
---

## Performance & Risk Dashboard

<img src="https://github.com/user-attachments/assets/9d615a52-bff3-479a-be16-34d0fea01aef">

---

# 📊 What Was Migrated?

<img src="https://github.com/user-attachments/assets/09e2383a-30d0-4de1-9981-f665717788f4" width="1000">

| Tableau Solution | Power BI Migration |
|-----------------|--------------------|
| KPI Cards | KPI Cards |
| LOD Expressions | DAX Measures |
| Tableau Relationships | Star Schema |
| Tableau Parameters | Power BI Slicers |
| Dashboard Actions | Cross Filtering |
| Table Calculations | Time Intelligence |
| User Filters | Row-Level Security |
| Interactive Dashboard | Interactive Dashboard |

---

# 🏗 Technical Migration Architecture

```
Excel MIS Files
        │
Power Query
(Data Cleaning)
        │
        ▼
Star Schema
───────────────
Fact_Wealth
Dim_Date
Dim_Manager
Dim_Product
Dim_Zone
───────────────
        │
        ▼
DAX Layer
───────────────
Achievement %
Revenue
Gap
Top N
Run Rate
Performance Bands
Zone Ranking
Product Contribution
───────────────
        │
        ▼
Power BI Report
```

---

# 📌 Business Logic Preserved

The migration intentionally retained identical KPI definitions across both BI platforms.

### Executive KPIs

- Achievement %
- Revenue
- Gap to Target
- Customer Count
- Active Clients
- Zone Ranking
- Product Contribution
- Product Mix
- Quarterly Trend
- Performance Bands
- Top Wealth Managers
- Q4 Run Rate
- Product Risk Analysis

This ensured leadership received identical business insights despite changing reporting platforms.

---

# ⚙ Technical Highlights

### Tableau Components Rebuilt

- LOD Expressions → DAX Measures
- Tableau Parameters → Power BI Slicers
- Tableau Calculations → DAX
- Tableau Relationships → Star Schema
- Dashboard Actions → Cross Filtering
- User Filters → Row-Level Security

---

### Power BI Features Used

- Star Schema Data Modeling
- Power Query
- DAX Measures
- Time Intelligence
- Row-Level Security (RLS)
- Drill Through
- Cross Filtering
- Conditional Formatting
- Dynamic KPI Cards
- Interactive Executive Dashboards

---

# 📈 Migration Outcomes

| Before | After |
|---------|--------|
| Manual Excel MIS | Automated Power BI Reporting |
| Multiple Excel Files | Single Semantic Model |
| Manual KPI Calculation | Automated DAX Measures |
| Static Reports | Interactive Dashboards |
| Monthly Reviews | Weekly Executive Monitoring |
| 3-Day Reporting | Same-Day Reporting |

---

# 💼 Business Impact

✅ Reporting turnaround reduced from **3 days to same-day delivery**

✅ Identified **39 at-risk Wealth Managers** before quarter-end

✅ Executive visibility across a **₹21.54 Billion AUM portfolio**

✅ Enabled zone-wise intervention planning

✅ Preserved identical KPIs across Tableau and Power BI

✅ Demonstrated platform-independent BI architecture

---

# 🚀 Skills Demonstrated

### Business

- Wealth Management Analytics
- Executive Reporting
- KPI Framework Design
- Banking MIS
- Performance Management

### SQL

- Data Cleaning
- ETL
- Window Functions
- Aggregations
- Business Rule Implementation

### Tableau

- LOD Expressions
- Dashboard Actions
- Interactive Storytelling

### Power BI

- Star Schema
- DAX
- Power Query
- Data Modeling
- Time Intelligence
- Row-Level Security
- Performance Optimization

---

# 📂 Repository Structure

```
Tableau-Power-BI-Migration/
│
├── Dataset/
├── SQL/
│   ├── Data_Cleaning.sql
│   └── Business_Queries.sql
│
├── Images/
│   ├── dashboard1.png
│   └── dashboard2.png
│
├── Wealth_MIS_Migration.pbix
│
└── README.md
```

---

# 🎯 Executive Takeaway

> **A dashboard can always be rebuilt.**
> **Business logic cannot.**

This project proves that when KPI definitions, semantic models, and transformation rules are properly governed, migrating from **Tableau to Power BI** becomes a controlled engineering exercise rather than a business risk.
---
## 👤 Author

**Aquib Tahil**
BI Analyst | Tableau Developer | 9 Years BFSI | Ex-ICICI Bank | Ex-Axis Bank
| Tableau Desktop Certified | MySQL | Power BI (PL-300 in progress)
---
