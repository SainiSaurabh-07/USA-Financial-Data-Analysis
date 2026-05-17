💳 USA Financial Data Analysis Dashboard

A dynamic, interactive Power BI report built to explore and analyze financial behavior, credit health, and loan patterns across age groups in the United States.

---

1. Short Description / Purpose

The USA Financial Data Analysis Dashboard is a visually engaging Power BI report designed to help analysts, financial institutions, and strategists explore credit behavior, loan distribution, and financial health metrics across different demographic segments. The dashboard focuses on key financial indicators such as credit utilization, payment behavior, credit score categories, and loan types — enabling data-driven decisions in consumer finance and risk management.

2.Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation and layout design.
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing raw financial data.
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, KPI cards, dynamic visuals, and conditional logic (e.g., segmenting customers by age group and credit mix).
- 📝 **Data Modeling** – Relationships established among tables to enable cross-filtering and aggregation across age, loan type, and credit behavior dimensions.
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.

3. Data Source

The dataset covers financial profiles of US consumers and includes details on income, credit scores, loan types, payment behavior, credit utilization, and demographic information by age group.

Key fields include:
- Age and age group classification (Teen, Young Adult, old1, old2, old Adult)
- Annual income and monthly balance
- Credit score categories (Above Standard, Standard, Good, Bad)
- Loan types (Auto, Mortgage, Student, Payday, Personal, Home Equity, Debt Consolidation, Credit-Builder)
- Payment behavior segmented by credit mix (High/Low spend × Large/Medium/Small value)
- Credit enquiry counts and credit utilization ratios

4. Features / Highlights

 ⚙️ Automated Data Pipeline

This dashboard is powered by a fully automated end-to-end data pipeline — from raw data collection to report delivery — eliminating manual effort and ensuring fresh insights every day.

| 📥 Data Collection | Microsoft Outlook | Daily financial data gathered automatically and consolidated into a dedicated folder |
| ☁️ Data Storage | Google Drive | Collected files stored and organized centrally for easy access and version control |
| 🔗 API Integration | Python | Custom-built API connects Power BI directly to Google Drive, enabling seamless and automated data refresh |
| 🔄 Data Processing | Power Query (Power BI) | Raw data cleaned, transformed, and reshaped into analysis-ready tables |
| 📊 Report Generation | Power BI Desktop | Dashboards built with key metrics and visuals, auto-generated from the processed data |

**Result**: The entire workflow — from data collection to report delivery — is fully automated. Reports are refreshed and delivered as live visuals every day at **8:00 PM**, providing stakeholders with real-time, actionable financial insights without any manual intervention.

5.Business Problem

Financial institutions and analysts often struggle to understand how credit behavior and loan preferences vary across different age demographics. Key questions such as:

- Which age groups carry the highest credit enquiry burden?
- How does payment behavior differ across credit mix categories?
- What is the distribution of loan types among potential customers?
- Which age segments show the most favorable or risky credit profiles?

…are difficult to answer quickly with raw transactional data.

---
6. Goal of the Dashboard

To deliver an interactive visual tool that:
- Enables exploration of financial behavior across age groups and credit categories.
- Supports risk assessment, customer segmentation, and targeted product strategy.
- Uncovers trends in payment behavior, credit health, and loan demand by demographic.

7. Walkthrough of Key Visuals

**Page 1 — Overview & Credit Behavior**

- **Key KPIs (Left Panel)**
  - Average Annual Income: **$167.11K**
  - Average Monthly Balance: **$404.36**
  - Average Delay in Payments: **21.20 days**
  - Average Credit Utilization Rate: **32.25%**

- **Age-Relation Trends in Credit Limit Adjustments** *(Line Chart)*
  Tracks average changed credit limits across individual ages, showing a declining trend from younger (age 17: ~13.9) to older customers (age 26: ~10.4). Useful for spotting when credit limit interventions are most common.

- **Count of Age by Age** *(Bar Chart)*
  Distribution of customer counts by age, with the highest concentration around ages 34–37 (600–700 customers), tapering off at older ages.

- **Credit Scores Across Age Groups** *(Small Multiples Bar Charts)*
  Four panels — Above Standard, Bad, Good, Standard — each showing count of customers per age group. Key insight: "old Adult" leads in Standard (1.5K) and Good (0.8K) categories, while Teens show relatively low counts across all score types.

- **Payment Behaviour Trends by Credit Mix** *(Grouped Bar Chart)*
  Compares payment behavior patterns (High/Low spend, Large/Medium/Small value) across four credit mix categories: Standard, Good, Above Standard, and Bad. "Good" credit mix shows the highest count at 1,127 in the High-spent Large-value category.

---

**Page 2 — Loan Analysis & Credit Enquiries**

- **Average Credit Enquiries by Age Group** *(Bar Chart)*
  Teens have the highest average credit enquiries (9.5), followed by old1 (7.8), old Adult (7.6), and Young Adult (7.6). old2 shows the lowest at 5.2 — indicating younger individuals apply for credit more frequently.

- **Loan Distribution Overview — Count by Loan Type** *(Table)*
  Displays customer count per loan type across 9 categories. Payday Loans and Personal Loans lead at 989 each, while Auto Loans are the lowest at 903. Total loan records: 2,665.

- **Age Analysis of Loan Customers by Credit Inquiries** *(Table)*
  Granular age-level breakdown showing all customers aged 14–29 are classified as "Potential Customers," with average credit enquiries ranging from ~7.5 to ~10.9. Overall average: **8.10**.

- **Average Number of Loans and Credit Cards per Age** *(Dual Line Chart)*
  Plots both average loan count and average credit card count across individual ages (16–55+). Credit card averages spike significantly at certain ages (e.g., age 30: 45.15), while loan averages remain relatively flat (3–5 range), revealing the diverging financial product adoption curve across life stages.

---

8.Business Impact & Insights

- **Risk Management**: Credit teams can identify high-risk age segments (e.g., Teens with high enquiry rates) and refine lending criteria accordingly.
- **Product Targeting**: Banks can tailor loan product campaigns — e.g., promoting Credit-Builder Loans to younger age groups with lower credit scores.
- **Customer Segmentation**: The payment behavior × credit mix analysis enables micro-segmentation for marketing and collections strategy.
- **Revenue Optimization**: Understanding which age groups hold more credit cards vs. loans helps product teams cross-sell effectively.
- **Portfolio Monitoring**: KPIs like average delay in payments (21.2 days) and credit utilization (32.25%) provide an at-a-glance portfolio health check.

---
9. Screenshots

**Page 1 — Overview & Credit Behavior**

![USA Financial Dashboard Page 1](https://github.com/SainiSaurabh-07/USA-Financial-Data-Analysis/blob/main/Screenshot%202026-05-05%20163223.png)
