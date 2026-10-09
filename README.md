\# 📊 Retail Customer Behavior \& Shopping Trends Analysis

An End-to-End Enterprise Data Analytics Project using Python, SQL, and Power BI.



\## 📌 Executive Summary \& Business Problem

A leading retail brand noticed subtle shifts in purchasing habits across demographics, changing product category performance, and fluctuating channel engagement. Management required a data-driven framework to answer a critical question: \*How can we leverage customer shopping data to identify high-value trends, minimize churn risk, and optimize target marketing campaigns?\*



This project simulates a complete, corporate-grade analytics lifecycle to process raw behavioral data, perform statistical cleaning, evaluate complex transactional relationships through relational SQL queries, and present interactive insights to C-suite stakeholders.



\---



\## 🛠️ Tech Stack \& Workflow Matrix

\* \*Data Engineering \& EDA:\* Python 3.x (pandas, numpy, matplotlib, seaborn)

\* \*Database \& Analytical Engine:\* MySQL / PostgreSQL (Window Functions, CTEs, Aggregations)

\* \*Business Intelligence:\* Power BI (DAX, Power Query, Star-Schema Data Modeling)

\* \*Stakeholder Delivery:\* Project Documentation, Gamma AI Presentation Deck



\---



\## 🚀 Step-by-Step Project Breakdown



\### 1. Data Cleaning \& Feature Engineering (Python)

Raw customer profiles were ingested and transformed inside an optimized pipeline:

\* \*Missing Value Imputation:\* Handled Review Rating gaps via category-wise median mapping.

\* \*Feature Engineering:\* Segmented Age into categorical buckets (Young Adult, Adult, Middle Aged, Senior) via pd.cut().

\* \*Normalization:\* Standardized naming syntax, unified inconsistent column cases, and dropped duplicate parameters.

\* See the full code implementation in /notebooks/data\_preprocessing\_eda.ipynb.



\### 2. Transactional Business Analytics (SQL)

Cleaned data was migrated into an operational database via SQLAlchemy. Key operational questions answered:

\* Identification of top-spending customer tiers via dynamic RFM quintiles.

\* Running calculation of historical customer revenue using analytical window functions.

\* Assessment of promotional code impacts on average order value (AOV).

\* Review full query sheets in /sql\_scripts/business\_queries.sql.




\### 3. Executive Dashboard Design (Power BI)

Built a dynamic corporate report to communicate findings instantly to leadership:

\* \*Core View:\* Total Sales, Active Customer Base, Average Satisfaction Rating, and Global AOV.

\* \*Demographics Map:\* Interactive visual slice filtering behavior by Age Group, Gender, and Season.

\* \*Loyalty \& Channel Drill-Down:\* Tracked shipping selection performance against return frequencies.


![Customer Review Dashboard](Customer%20review%20dashboard.png)


\---


\## 📈 Strategic Business Recommendations

1\. \*Targeted Micro-Campaigns:\* High-value 'Seniors' exhibit seasonal loyalty peaks; marketing spend should be shifted toward Q4 catalog distributions for this cohort.

2\. \*Channel Optimization:\* Direct-to-Consumer (DTC) mobile app sales showed a 14% drop in cart conversions when promotional tracking fields were missing. Ensure frictionless guest checkout paths.

