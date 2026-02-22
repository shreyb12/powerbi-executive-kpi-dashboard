# Executive KPI Dashboard (Power BI)

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Executive%20Dashboard-111?style=flat&logo=powerbi&logoColor=F2C811" />
  <img src="https://img.shields.io/badge/DAX-Measure%20Layer-111?style=flat" />
  <img src="https://img.shields.io/badge/Data%20Model-Star%20Schema-111?style=flat" />
  <img src="https://img.shields.io/badge/ETL-Power%20Query-111?style=flat" />
</p>

---

## Overview

A production-style executive dashboard built in Power BI to monitor commercial and operational performance across regions and product segments.

The solution follows a semantic model–first architecture, combining a clean star schema with structured DAX measures to deliver scalable, decision-ready reporting.

---

## Key Capabilities

- Executive KPI framework (Revenue, Volume, Margin, Operational metrics)
- Multi-year performance tracking with YoY and MoM variance analysis
- Drill-through navigation for root cause analysis
- Structured and reusable DAX measure layer
- Performance-optimized data model
- Executive-focused UX design

---

## Architecture

**Data Preparation**  
Power Query for transformation, shaping, and standardization.

**Data Model**  
Star schema design with fact tables and conformed dimensions.

**Calculation Layer**  
DAX measures for time intelligence, variance analysis, and contribution logic.

**Visualization Layer**  
Executive summary → Analytical breakdown → Detail drilldown.

---

## Business Value

- Accelerates executive decision-making through consolidated KPI visibility
- Reduces manual reporting effort with refresh-ready datasets
- Enables deeper analysis through structured drilldowns
- Supports scalable self-service reporting through clean modeling

---

## Screenshots

### Executive Overview
![Executive Overview](overview.png)

---

### Trends & Breakdown
![Trends & Breakdown](trends.png)

---

### Detail / Drilldown
![Detail / Drilldown](drilldown.png)

---

## Technical Highlights

- Time intelligence patterns (YTD, YoY %, Rolling trends)
- Variance analysis (Actual vs Target)
- Contribution analysis across hierarchical dimensions
- Controlled relationships and optimized measures
- Clean naming conventions and scalable measure organization
