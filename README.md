# 👥 Employee-Performance-Analysis Dashboard | Microsoft Fabric + Power BI

## 📊 Project Objective

To analyze global workforce data using Microsoft Fabric and provide actionable insights on turnover rates, compensation distribution, and employee performance to help HR and Finance leadership optimize retention and workforce spending.

## 🛠️ Tech Stack

- Data Orchestration: Microsoft Fabric Dataflows Gen2 & Pipelines
- Storage: Fabric Lakehouse
- Engine: SQL Analytics Endpoint & Direct Lake mode
- Visualization: Power BI Desktop
- Advanced Analytics: DAX, Field Parameters for dynamic dimension switching (Age Group, Department, Education, Job Level)

---

## 🛠️ Architecture & Lineage

- Ingestion: Raw HR data ingested from SQL Server via On-premises Data Gateway
- Transformation: Data cleaned and modeled in the Lakehouse using Power Query
- Semantic Layer: A Direct Lake semantic model optimized for high-performance reporting
- Reporting: High-impact dashboard featuring
- KPI Cards: Total Employees (7.5K), Annual Workforce Cost ($204.4M), Turnover Rate (19.9%)
- Geospatial Analysis: Employee distribution across the USA
- Dynamic Visuals: Bar charts utilizing Field Parameters to toggle between different employee attributes

<img width="2678" height="1414" alt="data_lineage" src="https://github.com/JyothiAnalytics/Employee-Performance-Fabric-Analytics/blob/main/Data_Lineage.png" />

---
## 📊 Dashboard

<img width="2678" height="1414" alt="emp_performance" src="https://github.com/JyothiAnalytics/Employee-Performance-Fabric-Analytics/blob/main/Emp_Performance_Dashboard.png" />

---
## 📈 Key Insights & Features
- Workforce Composition: Identification of Full-time vs. Contract staff ratios
- Salary Benchmarking: Analysis of salary bands (Medium, High, Low) across different management levels
- Trend Analysis: Tracking total employee growth from 2012 to 2022
- Demographic Deep-dive: Interaction between Age Groups and Gender to identify hiring trends

---

## 🎯 Business Recommendations

- Retention Targeting: Address the 19.9% Turnover Rate by identifying departments with the highest attrition and implementing "Stay Interviews" to protect top talent.
- Compensation Calibration: Audit the $204.4M Annual Cost against performance. Align "High Performers" in "Low Salary Bands" with market rates to prevent flight risk.
- Workforce Optimization: Evaluate the ratio of Full-Time vs. Contract staff. A conversion strategy can stabilize workforce costs and improve long-term culture.
- Productivity Benchmarking: Correlate Education & Training levels with performance scores. Redirect training budgets toward certifications that statistically drive higher output.

---

## 🏆 Conclusion

This Employee Performance Analysis project demonstrates how a modern data platform built on Microsoft Fabric can transform raw workforce data into a strategic business asset. By leveraging Direct Lake technology and Power BI visualization, the analysis successfully identified critical retention risks, compensation gaps, and workforce cost-saving opportunities. The project provides HR and Finance leadership with a high-performance, scalable solution to transition from reactive reporting to data-driven workforce planning and optimization.

The dashboard enables business users to interactively explore employee performance insights and make data-driven decisions.

---

**Made with ❤️ using Microsoft Fabric & Power BI**
