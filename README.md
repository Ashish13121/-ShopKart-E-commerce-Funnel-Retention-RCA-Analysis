# 🛒 ShopKart – E-commerce Funnel, Retention & RCA Analysis

## 1. Project Title & Overview

**ShopKart: E-commerce Funnel, Retention & Root Cause Analysis**

An end-to-end e-commerce analytics project designed to evaluate customer purchasing behavior, analyze conversion funnel performance, measure customer retention, and investigate potential friction points in the shopping journey.

The project uses MySQL, Advanced Excel, and Power BI to transform raw customer event data into meaningful business insights and actionable recommendations.

---

## 2. Business Problem & Project Objective

### Business Problem

E-commerce businesses often face challenges understanding customer behavior throughout the purchasing journey. Customers may drop off at different stages of the funnel, fail to complete payments, or stop returning to the platform.

Without proper analysis, identifying conversion bottlenecks and customer retention issues becomes difficult.

### Project Objectives

- Analyze customer movement across different stages of the shopping funnel.
- Identify conversion rates and customer drop-offs.
- Evaluate customer retention using Cohort Analysis.
- Compare funnel performance across acquisition channels and devices.
- Investigate payment-attempt and payment-success event discrepancies.
- Perform Root Cause Analysis (RCA) to identify potential friction points.
- Build interactive Power BI dashboards to communicate business insights.

---

## 3. Technology Stack

The project was developed using the following technologies:

- **MySQL:** Data querying, extraction, transformation, funnel analysis, cohort analysis, and RCA.
- **Advanced Excel:** Data cleaning, data analysis, Pivot Tables, lookup functions, and KPI analysis.
- **Power BI Desktop:** Interactive dashboard development and business data visualization.
- **Power Query:** Data cleaning and transformation.
- **DAX:** Calculated measures and dynamic KPI calculations.
- **Data Modeling:** Establishing relationships between tables for analytical reporting.

### SQL Concepts Used
- Joins
- Common Table Expressions (CTEs)
- Subqueries
- Aggregate Functions
- Window Functions
- CASE WHEN
- Date Functions
- GROUP BY and HAVING

---

## 4. Data Source & Dataset Overview

**Data Source:** Synthetic E-commerce Event Dataset

The dataset represents customer interactions and purchasing activities on an e-commerce platform.

**Dataset Size:**
- Total Users: 1,000
- Total Events: 3,058

The dataset contains customer event records used to analyze shopping journeys, acquisition channels, device preferences, and payment activities.

The data is synthetic and intended for analytical and portfolio purposes.

---

## 5. Key Features & Analytical Highlights

### A. Business Funnel Analysis
- Analyzed customer progression through different shopping journey stages.
- Calculated conversion rates across acquisition channels.
- Evaluated customer drop-offs during the purchasing journey.
- Compared funnel performance across devices and marketing channels.

### B. Cohort & Retention Analysis
- Grouped customers into cohorts based on their first activity.
- Evaluated customer engagement over subsequent periods.
- Analyzed retention patterns to understand returning customer behavior.

### C. Payment Funnel Analysis
- Compared payment-attempt events with payment-success events.
- Identified users with payment attempts but no corresponding recorded success events.
- Highlighted potential payment journey issues requiring further investigation.

### D. Root Cause Analysis (RCA)
- Investigated customer journey drop-offs.
- Examined potential friction points in the checkout and payment process.
- Developed data-driven recommendations for improving the purchasing experience.

---

## 6. Key Business Insights

The analysis identified the following findings:

**1. Acquisition Channel Performance**

- Google channel conversion rate: 76.92%
- Referral channel conversion rate: 83.87%

Referral showed a higher conversion rate than Google in the analyzed channel comparison.

**2. Payment Event Analysis**

- Users with payment-attempt events: 156
- Users without a corresponding recorded payment-success event: 20
- Percentage: 12.82%

This highlighted a potential gap in the payment journey that requires further investigation.

**3. Customer Retention**

Cohort analysis was performed to evaluate customer engagement and retention behavior over time.

---

## 7. Power BI Dashboard & Visualization

An interactive Power BI report is used to present the analytical findings and support business-level exploration.

The dashboard focuses on:

- Customer Funnel Performance
- Conversion Rate Analysis
- Acquisition Channel Comparison
- Device-wise Performance
- Customer Retention Analysis
- Payment Event Analysis
- Customer Journey Drop-offs

Interactive filters and visualizations enable users to explore different dimensions of customer behavior.

---

## 8. Business Recommendations

Based on the analytical findings, the following recommendations can be considered:

- Investigate the payment-attempt and payment-success event gap to determine whether it represents genuine payment friction or missing event tracking.
- Evaluate the checkout journey to identify stages with higher customer drop-offs.
- Study high-performing acquisition channels to understand their customer quality and conversion patterns.
- Use cohort retention findings to identify opportunities for improving repeat customer engagement.
- Monitor funnel conversion and payment completion metrics regularly.

---

## 9. Project Workflow

1. Dataset Understanding
2. Data Cleaning & Preparation
3. SQL-Based Data Analysis
4. Funnel & Conversion Analysis
5. Cohort & Retention Analysis
6. Payment Funnel Analysis
7. Root Cause Analysis
8. Advanced Excel Analysis
9. Power BI Dashboard Development
10. Business Insights & Recommendations

---

## 10. Project Outcome

Developed an end-to-end e-commerce analytics solution combining SQL-based analysis, Advanced Excel, and Power BI to evaluate customer journeys, measure funnel conversion, understand retention patterns, and identify potential payment-related friction points.

The project demonstrates practical data analysis skills, SQL querying, KPI evaluation, business problem-solving, and data visualization.

---

**Tools:** MySQL | Advanced Excel | Power BI | Power Query | DAX

**Project Type:** End-to-End Data Analytics | E-commerce Analytics
