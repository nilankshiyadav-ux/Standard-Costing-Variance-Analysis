# Standard Costing & Variance Analysis

### Illustrative Automobile Manufacturing Case Study | Microsoft Excel


## Project Overview

This project presents an **Excel-based Standard Costing and Variance Analysis model** developed around an illustrative automobile manufacturing case study, using **Maruti Suzuki India Limited** as the company context.

The model demonstrates how standard costing can be used to compare planned production costs with illustrative actual costs and identify the key drivers of cost differences.

The analysis covers:

* Direct material costs
* Direct labour costs
* Manufacturing overheads
* Favourable and adverse variances
* Overall cost reconciliation
* Management-level KPI reporting
* Dashboard-based visualisation

The project was developed as a **finance and accounting portfolio project** to demonstrate practical application of cost accounting concepts using Microsoft Excel.

> **Important:** Publicly available FY2025–26 Maruti Suzuki information is used only to establish company and industry context. The detailed standard and actual cost inputs used in the model are **illustrative modelling assumptions** and are not claimed to represent Maruti Suzuki's confidential, internal, or officially reported costing data.

---

# Business Problem

Manufacturing organisations need to monitor whether actual production costs are consistent with planned or standard costs.

When actual costs differ from standard costs, management needs to understand:

* What caused the difference?
* Was the variance caused by price or usage?
* Were labour rates higher than expected?
* Was labour utilisation efficient?
* Were manufacturing overheads controlled?
* Which cost category had the greatest impact on the overall result?

**Standard costing and variance analysis** provide a structured way to answer these questions.

This project applies that framework to an illustrative automobile manufacturing scenario and presents the results through an Excel-based analytical model.

---

# Project Objectives

The project was developed to:

1. Build a standard cost model for an illustrative automobile manufacturing scenario.
2. Develop a corresponding actual cost model.
3. Analyse material price and usage variances.
4. Analyse labour rate and efficiency variances.
5. Analyse manufacturing overhead variances.
6. Identify the major contributors to the overall cost variance.
7. Reconcile individual variances with the overall cost difference.
8. Present the analysis through a management-style Excel dashboard.
9. Demonstrate practical Excel, accounting and financial analysis skills.
10. Clearly distinguish public company information from illustrative modelling assumptions.

---

# Model Methodology

The model follows a structured cost-analysis workflow:

```text
Public Company & Industry Context
                ↓
       Source Classification
                ↓
        Standard Cost Model
                ↓
          Actual Cost Model
                ↓
       Material Variance
                ↓
        Labour Variance
                ↓
       Overhead Variance
                ↓
        Variance Summary
                ↓
     Overall Reconciliation
                ↓
       Dashboard & Findings
```

The standard cost represents the benchmark cost for the illustrative production scenario.

The actual cost represents the illustrative cost incurred under the model's assumptions.

The difference between the two is analysed through individual variance components.

---

# Excel Workbook Structure

The completed workbook contains **9 sheets**:

| #  | Sheet                    | Purpose                                           |
| -- | ------------------------ | ------------------------------------------------- |
| 01 | **Project Info**         | Project scope, purpose and overview               |
| 02 | **Assumption & Sources** | Sources, assumptions and data classification      |
| 03 | **Standard Cost**        | Standard quantities, rates and standard cost      |
| 04 | **Actual Cost**          | Actual quantities, rates and actual cost          |
| 05 | **Material Variance**    | Material price and usage variance                 |
| 06 | **Labour Variance**      | Labour rate and efficiency variance               |
| 07 | **Overhead Variance**    | Overhead expenditure and efficiency variance      |
| 08 | **Variance Summary**     | Consolidated variance analysis and reconciliation |
| 09 | **Dashboard**            | KPIs, charts and key findings                     |

---

# Variance Analysis

## Material Variance

The model analyses two material variances.

### Material Price Variance

Measures the effect of paying a different price from the standard price.

```text
Material Price Variance
= Actual Quantity × (Standard Price − Actual Price)
```

### Material Usage Variance

Measures the effect of using more or less material than the standard quantity allowed.

```text
Material Usage Variance
= Standard Price × (Standard Quantity − Actual Quantity)
```

### Result

| Material Variance           |                 Amount |
| --------------------------- | ---------------------: |
| Price Variance              |     ₹25,30,000 Adverse |
| Usage Variance              |      ₹5,50,000 Adverse |
| **Total Material Variance** | **₹30,80,000 Adverse** |

---

# Labour Variance

The model analyses labour cost through rate and efficiency variances.

### Labour Rate Variance

```text
Labour Rate Variance
= Actual Hours × (Standard Rate − Actual Rate)
```

### Labour Efficiency Variance

```text
Labour Efficiency Variance
= Standard Rate × (Standard Hours − Actual Hours)
```

### Result

| Labour Variance          |                Amount |
| ------------------------ | --------------------: |
| Rate Variance            |     ₹4,35,000 Adverse |
| Efficiency Variance      |  ₹1,50,000 Favourable |
| **Labour Cost Variance** | **₹2,85,000 Adverse** |

---

# Overhead Variance

The model includes:

* Overhead Expenditure Variance
* Overhead Efficiency Variance

### Result

| Overhead Variance           |                   Amount |
| --------------------------- | -----------------------: |
| Expenditure Variance        |       ₹37,500 Favourable |
| Efficiency Variance         |       ₹62,500 Favourable |
| **Total Overhead Variance** | **₹1,00,000 Favourable** |

---

# Overall Results

The completed model produces the following results:

| KPI                      |                 Result |
| ------------------------ | ---------------------: |
| **Standard Cost**        |          ₹13,38,75,000 |
| **Actual Cost**          |          ₹13,71,40,000 |
| **Overall Variance**     | **₹32,65,000 Adverse** |
| **Variance per Vehicle** |     **₹3,265 Adverse** |
| **Reconciliation**       |       **CHECK PASSED** |

### Overall Interpretation

The illustrative actual production cost is higher than the standard cost by **₹32.65 lakh**, resulting in an overall **adverse variance**.

The major contributor is material cost, followed by labour cost.

Overhead performance is favourable and partially offsets the adverse material and labour variances.

---

# Key Findings

### 1. Material cost is the largest adverse contributor

Total material variance is **₹30.80 lakh adverse**, representing the largest contributor to the overall cost difference.

The material variance consists of:

* ₹25.30 lakh adverse price variance
* ₹5.50 lakh adverse usage variance

The price variance is therefore the primary material-related driver in the illustrative model.

### 2. Labour cost is net adverse

Labour produces a **₹2.85 lakh adverse variance**.

Although labour efficiency is favourable by ₹1.50 lakh, the ₹4.35 lakh adverse labour rate variance more than offsets the efficiency benefit.

### 3. Overheads are favourable

Total overhead variance is **₹1.00 lakh favourable**.

Both expenditure and efficiency variances are favourable in the model.

### 4. Overall cost position is adverse

The combined effect produces:

**₹32.65 lakh Adverse**

or:

**₹3,265 Adverse per vehicle**

### 5. Reconciliation control passed

The model contains a reconciliation control confirming that the component-level variance analysis agrees with the overall variance.

**CHECK PASSED**

---

# Dashboard

The workbook includes a dedicated management-style dashboard containing:

* Standard Cost KPI
* Actual Cost KPI
* Overall Variance KPI
* Variance per Vehicle KPI
* Variance comparison charts
* Key findings
* Reconciliation status

![Project Dashboard](https://github.com/nilankshiyadav-ux/Standard-Costing-Variance-Analysis/blob/main/Screenshots/Dashboard.png)

---

# Project Screenshots

## Standard Cost Model
[ Standard cost ](https://github.com/nilankshiyadav-ux/Standard-Costing-Variance-Analysis/blob/main/Screenshots/standard_cost.png)
 
## Material Variance Analysis

![Material Variance](https://github.com/nilankshiyadav-ux/Standard-Costing-Variance-Analysis/blob/main/Screenshots/material_variance.png)

## Labour Variance Analysis

![Labour Variance](https://github.com/nilankshiyadav-ux/Standard-Costing-Variance-Analysis/blob/main/Screenshots/labour_variance.png)

## Overhead Variance Analysis

![Overhead Variance](https://github.com/nilankshiyadav-ux/Standard-Costing-Variance-Analysis/blob/main/Screenshots/overheads_variance.png)

## Variance Summary

![Variance Summary](https://github.com/nilankshiyadav-ux/Standard-Costing-Variance-Analysis/blob/main/Screenshots/variances_summary.png)

---

# Company Context

The case study uses **Maruti Suzuki India Limited** as the company context.

Publicly available FY2025–26 information used for contextual reference includes:

| Metric      |               FY2025–26 |
| ----------- | ----------------------: |
| Production  | Over 23.4 lakh vehicles |
| Total Sales |      2,422,713 vehicles |
| Net Sales   |      ₹1,743,695 million |
| Net Profit  |        ₹144,454 million |

These figures provide context for the scale of the automobile manufacturing business.

They are **not used to imply that the detailed cost assumptions in this project represent Maruti Suzuki's actual internal production costing**.

---

# Data Sources & Assumptions

The project deliberately separates information into three categories.

## 1. Publicly Reported Company Data

Public Maruti Suzuki information is used for company-level context, including:

* Production
* Total sales
* Net sales
* Net profit

## 2. Industry / Benchmark Context

Government of India / Ministry of Steel / JPC information was used as benchmark context for steel pricing.

Industry information is used to provide context when developing illustrative assumptions.

## 3. Portfolio Modelling Assumptions

The detailed standard and actual cost inputs are illustrative assumptions created specifically for this project.

These include assumptions relating to:

* Material quantities
* Material prices
* Labour hours
* Labour rates
* Overhead costs
* Standard costs
* Actual costs

### Steel Quantity Assumption

The steel quantity used in the model is an **industry-informed illustrative assumption**.

Vehicle weight is used only as contextual reference.

The model does **not** claim that this quantity represents Maruti Suzuki's:

* Actual steel consumption
* Actual bill of materials
* Actual procurement quantity
* Actual production standard
* Internal material usage

This distinction is intentionally maintained throughout the project.

---

# Tools & Skills Demonstrated

## Tools

* Microsoft Excel
* Excel formulas
* Excel charts
* Excel dashboard development

## Accounting & Finance

* Cost Accounting
* Standard Costing
* Variance Analysis
* Cost Control
* Management Accounting
* Financial Analysis
* Cost Reconciliation
* KPI Analysis
* Management Reporting

## Excel / Analytical Skills

* Structured workbook design
* Formula-based modelling
* Financial calculations
* Variance calculations
* Reconciliation controls
* Dashboard design
* Data classification
* Data interpretation
* Visual reporting

---

# Project Files

### Excel Model

**[Open the complete Excel workbook](Excel/Standard_Costing_Variance_Analysis.xlsx)**

The workbook contains all nine completed sheets, calculations, dashboard and reconciliation controls.

### Detailed Documentation

**[Read the Project Notes](https://github.com/nilankshiyadav-ux/Standard-Costing-Variance-Analysis/blob/main/Documentation/Project%20Notes.pdf)**

The Project Notes contain detailed methodology, formula explanations, assumptions, source classification, limitations and interpretation.

---

# Disclaimer

> **This is an educational and portfolio modelling project. Maruti Suzuki India Limited is used as the company context only. The standard quantities, actual quantities, rates, costs and detailed variance inputs are illustrative modelling assumptions and are not confidential, internal, or officially reported Maruti Suzuki costing data. Publicly available company and industry information is used only to provide contextual reference and benchmark support.**

---

# Project Purpose

This project was developed as part of a personal **finance and accounting portfolio** to demonstrate practical application of cost accounting and Excel-based financial analysis.

It is intended to demonstrate analytical methodology, Excel modelling, accounting knowledge and professional presentation rather than reproduce a real company's internal costing system.

---

# Author

**Nilankshi Yadav**

B.Com. Student
Accounting & Finance | Excel | Financial Analysis

---

**Project:** Standard Costing & Variance Analysis
**Platform:** Microsoft Excel
**Category:** Cost Accounting / Financial Analysis
**Project Type:** Portfolio / Illustrative Case Study
