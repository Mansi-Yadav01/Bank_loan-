# Bank_loan-

💰 Bank Loan Analysis Dashboard

An interactive, analytical Power BI dashboard designed to explore and monitor loan performance—focusing on loan applications, funding, repayments, borrower risk profiles, and overall portfolio health.

📝 Short Description / Purpose

The Bank Loan Analysis Dashboard provides a comprehensive view of loan operations, helping financial analysts, credit officers, and business managers track loan applications, funded amounts, repayments, and loan quality. The dashboard highlights patterns in borrower behavior, loan purposes, repayment performance, and regional distribution, enabling data-driven decisions to reduce defaults and boost loan applications.

⚙️ Tech Stack

This dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Core platform for building reports and visuals.

📂 Power Query – For cleaning, transforming, and reshaping raw loan data.

🧠 DAX (Data Analysis Expressions) – To create KPIs such as funded vs. received amounts, good vs. bad loan percentages, and DTI calculations.

📝 Data Modeling – Relationships established between borrower details, loan performance, and repayment tables for cross-filtering.

💾 MySQL  – Used for database creation, query writing, and initial data preparation.

📁 File Formats – .pbix for Power BI dashboard, .png for preview screenshots.

📂 Data Source

Source: Kaggle.

The dataset includes:

Loan applications (ID, issue date, amount).

Borrower demographics (employment length, home ownership).

Loan attributes (purpose, grade, term, interest rate, DTI).

Performance outcomes (funded amount, repayments, loan status).

🌟 Features / Highlights
🔴 Business Problem

The bank has issued 38.6K loan applications worth $436M, but faces:

A 13.3% bad loan ratio, causing significant losses.

Over-concentration in debt consolidation loans and high-tenure employees.

Weak customer retention, with only ~1K “current” loans compared to 32K fully paid.

Missed opportunities in younger borrowers, diverse loan purposes, and mid-risk credit grades.

🎯 Goal of the Dashboard

To deliver an interactive visual tool that:

Tracks loan KPIs like funded vs. received, interest rates, and DTIs.

Monitors portfolio quality by good vs. bad loans and repayment status.

Analyzes borrower demographics, purposes, and regions to identify underserved markets.

Provides insights to reduce defaults and increase loan applications sustainably.

📊 Walkthrough of Key Visuals
Top KPIs (Summary Dashboard)

Total Applications: 38.6K

Total Funded: $436M

Total Received: $473M

Avg Interest Rate: 12.05%

Avg DTI: 13.3%
👉 Insight: Repayments are healthy overall, but bad loans drag profitability.

Good vs Bad Loan Donuts

Good Loans: 86.7%

Bad Loans: 13.3%
👉 Insight: Defaults are significant—bad loans funded = $66M but received only $37M.

Loan Status (Grid View)

Fully Paid: 32K

Current: 1K

Charged Off: 533
👉 Insight: Most customers can repay → strong case for expanding loan base.

Grade Analysis (Line Chart)

Grades A–C dominate, Grades D–G almost absent.
👉 Insight: Too risk-averse; missing out on mid-risk, high-return segments.

Loan Purpose Breakdown (Bar Chart)

Debt Consolidation = $0.21B (50%+).
👉 Insight: Portfolio overly dependent on one purpose; need to diversify.

Employee Tenure (Bar Chart)

10+ years employees = $105M.
👉 Insight: Younger employees under-served, potential untapped market.

Home Ownership (Treemap)

Mortgage holders = $207M.
👉 Insight: Homeowners (safer borrowers) not fully tapped.

Regional Map

Loans concentrated in specific states.
👉 Insight: Regional disparities → some states show strong demand, others underpenetrated.

📈 Business Impact & Insights

Risk Management: High DTI and debt consolidation loans drive most defaults → screening rules must tighten.

Growth Potential: Expanding into younger employees, diverse loan purposes, and mid-risk credit grades can boost applications.

Customer Retention: Pre-approved offers for fully paid borrowers can convert them into repeat customers.

Regional Expansion: Low-loan states present opportunities for growth with targeted campaigns.

🚀 Solution Strategies to Increase Loan Applications

Diversify Loan Products → Promote education, vehicle, and small business loans.

Tap Younger Borrowers → Launch starter loans for early-career employees and freelancers.

Risk-Based Pricing → Expand into mid-risk credit grades with capped loan sizes and higher rates.

Customer Loyalty Programs → Offer pre-approved top-up loans for good borrowers.

Regional Targeting → Focus marketing in under-served states with lower default rates.

📸 Screenshots / Demos

Summary : ""
Overview : ""
