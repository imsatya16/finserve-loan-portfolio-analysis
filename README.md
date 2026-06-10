# finserve-loan-portfolio-analysis
# 📊 FinServe Loan Portfolio Analysis

## Overview

This project analyzes the loan portfolio of FinServe Lending Co., a multi-region lending company operating across India. The objective was to transform raw and inconsistent loan data into meaningful business insights through data cleaning, risk assessment, portfolio analysis, and dashboard development.

The project simulates a real-world business analytics scenario where management requires visibility into loan exposure, borrower risk, repayment performance, and regional trends to support better lending decisions.

---

## Business Problem

FinServe's management observed:

* Increasing late repayments and loan defaults
* Lack of centralized portfolio visibility
* Difficulty identifying high-risk borrowers
* Limited branch-level performance monitoring

The analytics team was tasked with cleaning the loan data, performing risk analysis, and creating an interactive dashboard for management reporting.

---

## Dataset Information

| Metric             | Value                                               |
| ------------------ | --------------------------------------------------- |
| Total Loan Records | 1,215                                               |
| Regions            | 5                                                   |
| Branches           | 25                                                  |
| Loan Products      | Home, Vehicle, Education, Personal & Business Loans |
| Analysis Tool      | Microsoft Excel                                     |

### Key Fields

* Loan ID
* Customer Name
* Employment Type
* Monthly Income
* Loan Amount
* Credit Score
* Loan Status
* Repayment Status
* Region
* Branch
* Outstanding Balance

---

## Tools & Techniques Used

### Microsoft Excel

* Excel Tables
* Pivot Tables
* Pivot Charts
* Slicers
* Timeline Filters
* Conditional Formatting

### Excel Functions

* TRIM()
* CLEAN()
* SUBSTITUTE()
* PROPER()
* IF()
* IFS()
* XLOOKUP()
* INDEX()
* MATCH()
* DATEDIF()
* EDATE()
* ROUND()

---

## Data Cleaning & Preparation

The raw dataset contained several data quality issues which were resolved before analysis.

### Data Cleaning Activities

✅ Removed duplicate Loan IDs

✅ Trimmed extra spaces from customer names

✅ Standardized Employment Type formatting

✅ Cleaned hidden characters from Loan Purpose

✅ Handled missing Credit Scores

✅ Corrected inconsistent date formats

✅ Standardized Branch names

✅ Converted dataset into structured Excel Tables

---

## Feature Engineering

Several business metrics were created to support analysis.

| Feature           | Purpose                           |
| ----------------- | --------------------------------- |
| Days to Approval  | Loan processing efficiency        |
| Loan Age (Months) | Portfolio aging analysis          |
| Maturity Date     | Loan lifecycle tracking           |
| Is Matured        | Active vs Matured loans           |
| DTI Ratio         | Debt-to-Income analysis           |
| DTI Risk Flag     | Borrower affordability assessment |
| Risk Category     | Credit risk classification        |
| Risk Code         | Risk categorization               |
| Branch Manager    | Branch-level lookup mapping       |

---

## Business Questions Answered

### Portfolio Exposure Analysis

* Total loan amount disbursed
* Average loan size by region
* Outstanding balance by region
* Highest exposure region

### Risk Analysis

* Distribution of borrowers by risk category
* Identification of High-Risk and Very High-Risk customers
* Risk concentration analysis

### Repayment Performance

* Default analysis
* Late payment trends
* Repayment behavior across employment types

### Branch Analysis

* Branch-wise loan exposure
* Branch-wise high-risk customer concentration
* Branch performance comparison

### Trend Analysis

* Monthly loan application trends
* Loan approval tracking
* Portfolio growth analysis

---

## Dashboard Features

The interactive dashboard includes:

* Loan Distribution by Region
* Portfolio Risk Segmentation
* Repayment Performance by Employment Type
* Region Slicer
* Loan Status Slicer
* Application Date Timeline Filter
* Dynamic Pivot Charts

---

## Dashboard Preview

### Main Dashboard

Replace the image path below after uploading your dashboard screenshot.

![Dashboard](Dashboard/Dashboard.png)

---

## Key Skills Demonstrated

* Business Analytics
* Financial Analysis
* Risk Assessment
* Data Cleaning
* Data Visualization
* Dashboard Development
* KPI Reporting
* Pivot Table Analysis
* Loan Portfolio Analysis
* Decision Support Reporting
* Excel Dashboard Design

---

## Business Impact

This project demonstrates how raw lending data can be transformed into actionable insights that help management:

* Monitor portfolio health
* Identify risky borrowers
* Reduce lending exposure
* Track repayment performance
* Support data-driven lending decisions
* Improve portfolio monitoring through interactive reporting

---

## Repository Structure

finserve-loan-portfolio-analysis

├── README.md

├── Dataset

│ └── FinServe_Loan_Portfolio_Dataset.xlsx

├── Dashboard

│ ├── Dashboard.png

│ ├── Risk_Distribution.png

│ ├── Loan_Exposure.png

│ └── Repayment_Performance.png

├── Documentation

│ └── FinServe_Case_Study.pdf

└── Insights

└── Business_Insights.pdf

---

## Author

### Satyabrata Sahoo

MBA (Information Technology & Systems Management)

Business Analytics | Data Analytics | Excel | SQL | Power BI | Python

LinkedIn:
https://www.linkedin.com/in/imsatya16/

GitHub:
https://github.com/imsatya16

---

## Project Status

✅ Completed

This project was developed as part of a Business Analytics case study focused on loan portfolio management, risk assessment, and executive dashboard reporting using Microsoft Excel.

