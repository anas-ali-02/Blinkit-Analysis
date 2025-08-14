# Blinkit_Analysis  
Retail Domain | Blinkit Sales & Performance Analysis  

This repository contains the code and documentation for the Blinkit Analysis project. Below you'll find the domain knowledge in `domain_knowledge.md`, the problem statement in `problem_statement.md`, and an overview of the solution implemented using SQL and Power BI.  

## Domain Knowledge  

To read the domain knowledge, please refer to [![Domain Knowledge](https://img.shields.io/badge/Domain%20Knowledge-blue)](domain_knowledge.md)  

## Problem Statement  

To read the problem statement, please refer to [![Problem Statement](https://img.shields.io/badge/Problem%20Statement-blue)](problem_statement.md)  

---

### Power BI Implementation  

Click the button below to view the Power BI dashboard:  

[![View Dashboard](https://img.shields.io/badge/View%20Dashboard-Click%20Here-blue)](YOUR_DASHBOARD_LINK)  

---

### SQL Implementation  

# KPI's  

### 1. Total Sales  

```sql
SELECT ROUND(SUM(sales), 2) AS Total_Sales
FROM blinkit_data;
