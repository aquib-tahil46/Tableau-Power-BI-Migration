# Tableau-Power-BI-Migration
It demonstrates how an enterprise Wealth Management MIS can be migrated from Excel → Tableau → Power BI while preserving business logic, KPIs, and executive reporting standards.
## Why this project?
This repository is not simply another Power BI dashboard.
It demonstrates how an enterprise Wealth Management MIS can be migrated from Excel → Tableau → Power BI while preserving business logic, KPIs, and executive reporting standards.
Instead of redesigning reports from scratch, the objective was to prove that a governed BI solution should remain consistent regardless of visualization platform.

## Migration Journey
Manual Excel MIS
        │
        ▼
Data Cleaning (SQL)
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
Production Ready Executive Dashboard
What Was Migrated?
Component               	    Tableau Version             	 Power BI Version
Executive KPI Cards	               ✅                           	✅
Zone Ranking	                LOD Expressions            	    DAX Measures
Performance Segmentation	  Sets + Calculations    	    DAX + Conditional Formatting
Product Risk Matrix	           Scatter Plot	                  Scatter Visual
Executive Filters	            Context Filters	                  Slicers
Dashboard Actions	            Tableau Actions               	Cross Filtering
Quarterly Trend	            Table Calculations             	Time Intelligence
Security	Tableau User Filters	Row-Level Security (RLS)
Data Model	Tableau Relationships	Star Schema
Migration Architecture
Excel Wealth MIS
<img width="379" height="260" alt="image" src="https://github.com/user-attachments/assets/92a63e13-3898-4746-85d0-8125996d1ced" />

        │
Power Query
(Data Cleaning)

        │

Star Schema
──────────────
Fact_Wealth
Dim_Date
Dim_Manager
Dim_Product
Dim_Zone

        │

DAX Layer
──────────────
Achievement %
Gap
Revenue
Q4 Run Rate
Performance Band
Zone Ranking
Product Contribution
Top N Analysis

        │

Power BI Report

Executive Dashboard
Business Dashboard
Business Logic Preserved

The migration intentionally retained identical KPI definitions across both BI platforms.

Executive KPIs
Total AUM
Revenue
Achievement %
Gap to Target
Product Mix
Zone Ranking
Quarterly Growth
Performance Bands
Top Wealth Managers
Product Contribution
Q4 Run Rate
Risk Identification

This ensured business users received identical insights despite the underlying reporting platform changing.

Technical Migration Highlights
Tableau Components Rebuilt
LOD Expressions → DAX Measures
Tableau Parameters → Power BI Slicers
Tableau Calculations → DAX
Tableau Dashboard Actions → Cross Filtering
Tableau Relationships → Star Schema
Tableau Calculated Fields → Measures & Calculated Columns
Power BI Features Implemented
Star Schema Modeling
Power Query ETL
DAX Measures
Time Intelligence
Row-Level Security (RLS)
Dynamic KPIs
Drill-through Navigation
Cross-filtering
Conditional Formatting
Interactive Executive Dashboard
Migration Outcomes
Before	After
Manual Excel Reporting	Automated Power BI Reporting
Static Reports	Interactive Dashboards
Multiple Excel Files	Single Semantic Model
Manual KPI Calculation	Automated DAX Measures
Separate Department Reports	Unified Executive Dashboard
3-Day Reporting Cycle	Same-Day Reporting
Business Impact

✔ Reporting turnaround reduced from 3 days to same-day delivery

✔ Identified 39 at-risk Wealth Managers before quarter-end

✔ Executive leadership gained real-time visibility into a ₹21.54B portfolio

✔ Zone-level performance monitoring enabled targeted interventions

✔ Successfully migrated the same governed KPI framework across three platforms

Excel
      ↓
Tableau
      ↓
Power BI

without changing business definitions.

Key Learning

Business Intelligence is not about dashboards.

It is about creating governed business logic that survives changes in technology.

A well-designed semantic model, documented KPIs, and standardized calculations make platform migration predictable rather than disruptive.

Skills Demonstrated
Business
Wealth Management Analytics
Executive Reporting
KPI Framework Design
Performance Management
Banking MIS
Decision Support
SQL
Data Cleaning
ETL
Aggregations
Window Functions
Business Rule Implementation
Tableau
LOD Expressions
Dashboard Actions
Interactive Storytelling
Power BI
Star Schema
DAX
Power Query
Time Intelligence
RLS
Data Modeling
Performance Optimization
Repository Structure
wealth-mis-powerbi-migration/
│
├── Power BI Dashboard.pbix
├── SQL/
│     ├── Data Cleaning.sql
│     ├── Business Queries.sql
│
├── Dataset/
│
├── Images/
│
├── README.md
│
└── Dashboard Screenshots
Executive Takeaway

A dashboard can be rebuilt. Business logic cannot be improvised.

This project demonstrates that when KPIs, data models, and transformation rules are properly governed, migrating from Tableau to Power BI becomes a controlled engineering exercise—not a business risk.
