# Telco Customer Churn Analysis Dashboard \| Power BI

## Project Overview

This project analyzes customer churn in a telecommunications dataset
using Microsoft Power BI. The dashboard explores churn patterns across
customer contracts, internet services, payment methods, and customer
tenure to identify higher-risk customer segments and support data-driven
retention planning.

## Business Objectives

-   Measure the overall customer churn rate.
-   Compare churn across contract types and internet service types.
-   Understand how customer tenure relates to churn.
-   Examine churn patterns by payment method and monthly charges.
-   Identify customer segments that may benefit from targeted retention
    efforts.

## Dataset Overview

-   **Dataset:** Telco Customer Churn
-   **Records:** 7,043 rows
-   **Fields:** 21 columns

Key fields used in the analysis include Customer, Contract, Internet
Service, Payment Method, Tenure, Monthly Charges, and Churn.

## Tools and Technologies

-   **Microsoft Power BI** --- interactive dashboard development and
    visual analysis
-   **Power Query** --- data cleaning and preparation
-   **DAX** --- measures and KPI calculations
-   **Microsoft Excel** --- dataset/workbook handling

## Data Preparation

The project presentation documents these preparation steps in Power
Query:

-   Checked and corrected data types.
-   Identified and handled blank or null values.
-   Removed duplicate records.
-   Validated categorical and numerical fields.
-   Prepared the data for DAX calculations and visualization.
-   Documented transformations in Power Query Applied Steps.

## Dashboard Analysis

The project includes an overview dashboard and a customer-focused
dashboard. The analysis considers churn by contract type, internet
service, payment method, and tenure.

### Key Findings

The findings below are reported in the project presentation:

-   **Overall churn:** 26.58% of customers had churned.
-   **Contract type:** Month-to-month customers had the highest churn,
    at approximately 43%, compared with 11% for one-year contracts and
    3% for two-year contracts.
-   **Internet service:** Fiber optic customers had the highest churn,
    at approximately 42%, compared with 19% for DSL and 7% for customers
    without internet service.
-   **Payment method:** Electronic-check customers had a churn rate of
    approximately 34%, compared with 15% for credit-card customers.
-   **Tenure:** Churn was more concentrated among newer customers and
    generally decreased as tenure increased.

These are observed patterns in the dataset and do not, by themselves,
prove causation.

## Recommendations

Based on the analysis, the project proposes the following actions:

1.  **Target month-to-month customers:** Develop targeted offers that
    encourage suitable customers to move to longer-term contracts.
2.  **Improve early customer experience:** Strengthen onboarding and
    engagement during the first months of the customer lifecycle.
3.  **Review payment experience:** Investigate the billing experience of
    electronic-check customers and promote convenient payment options.
4.  **Use segmented retention campaigns:** Tailor campaigns using
    contract, service, tenure, and payment characteristics.

## How to View the Project

1.  Download or clone this repository once the project files have been
    uploaded to GitHub.
2.  Open `CUSTOMERCHURN PROJ.pbix` using Microsoft Power BI Desktop.
3.  If Power BI requests the source workbook, use the included Excel
    file and update the data-source path as needed.
4.  Refresh the data if required, then explore the dashboard visuals and
    filters.
5.  Refer to `Telco Customer Churn Presentation.pptx` for the project
    methodology, findings, and recommendations.

> **Note:** File names and data-source paths may need to be adjusted to
> match the final repository structure.

## Limitations and Future Work

The project presentation notes these limitations:

-   The analysis is based on the available customer churn dataset.
-   Observed relationships do not necessarily prove causation.
-   Some potential churn drivers may not be represented in the dataset.

Possible next steps include monitoring churn trends over time,
developing stronger customer-risk scoring, investigating high-risk
segments, testing targeted retention campaigns, and measuring whether
retention actions reduce churn.

## Project Files

The project materials include:

-   `CUSTOMERCHURN PROJ.pbix` --- Power BI report
-   `power bi -Telco-Customer-Churn.xlsx` --- Excel workbook / dataset
-   `Telco Customer Churn Presentation.pptx` --- project presentation

## Author

**Muhammed Muflih**

------------------------------------------------------------------------

*Created as a customer churn analysis and business intelligence project
using Microsoft Power BI.*
