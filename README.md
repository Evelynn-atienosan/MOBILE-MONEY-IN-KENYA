# Mobile Money in Kenya: Financial Inclusion Analytics (2021–2024)

> **How mobile money evolved from an alternative payment solution into the foundation of Kenya's digital financial ecosystem.**

## Executive Summary

Kenya has become the global benchmark for mobile money adoption. When the World Bank Group's Global Findex Database first measured mobile money ownership in Sub-Saharan Africa, Kenya not only led the region but also the world. At the time, **58% of adults owned a mobile money account**, surpassing the **55% who owned a traditional bank account**. Driven by Safaricom's M-Pesa platform, Kenya demonstrated how digital financial services could dramatically accelerate financial inclusion.

A decade later, that transformation has continued. By 2024, **87% of Kenyan adults owned a mobile money account**, contributing to an overall **90% financial account ownership rate**.

   <img width="538" height="290" alt="Account_Ownership" src="https://github.com/user-attachments/assets/aaf5c650-f0be-4755-980b-938425ab8df2" />


However, this project reveals that the real story extends beyond account ownership. Between 2021 and 2024, mobile money increasingly became the preferred platform for saving, accessing formal credit, and receiving wages, fundamentally changing how millions of Kenyans interact with financial services.



# Project Objective

The objective of this project was to analyze how financial behavior in Kenya evolved between 2021 and 2024 by examining the relationship between mobile money and traditional banking.

Instead of relying solely on aggregated indicators, this project applies set theory to isolate overlapping financial metrics, providing a clearer understanding of how adults save, borrow, receive wages, and access financial services.



# Methodology

1. Downloaded sub-saharan Africa and filtered the data to Kenya-specific financial inclusion indicators from the **World Bank Global Findex Database**.
2. Selected indicators covering account ownership, savings, borrowing, and wage payments.
3. Cleaned and standardized each dataset using **Python (Pandas)**.
4. Merged multiple indicator tables into a single master dataset.
5. Performed Exploratory Data Analysis (EDA) to validate data quality and identify trends.
6. Applied **set theory** to remove overlapping populations and derive mutually exclusive financial categories (e.g., Mobile Money Only, Bank Only, Both, Informal).
7. Exported the final analytical datasets as CSV files.
8. Imported the cleaned datasets into **Power BI** to build interactive visualizations.


# Tools & Technologies

* **Python**
  * Pandas
  * NumPy
  * Matplotlib
  * Jupyter Notebook
  * Seaborn

* **Power BI**
  * Data Modeling
  * Interactive Dashboards

* **Data Source**
  * World Bank Global Findex Database

* **Techniques**
  * Data Cleaning
  * Exploratory Data Analysis (EDA)
  * Set Theory
  * Data Transformation
  * Data Visualization

# Changing Savings Patterns in the Mobile Money Era

Between 2021 and 2024, Kenyan households significantly changed where they stored their money.

Although the proportion of adults saving increased modestly from **66.77% to 70.19%**, traditional bank-only savings nearly halved, declining from **7.77% to 3.95%**. Informal saving methods such as storing cash at home or participating in community savings groups also fell from **21.76% to 15.77%**.

Meanwhile, exclusive mobile money savings increased sharply from **23.56% to 34.27%**, making digital wallets the country's most widely used savings channel. Adults combining both bank accounts and mobile money also grew slightly from **13.69% to 16.20%**.

**Key Insight:** Mobile money has become the preferred destination for household savings, attracting users from both traditional banking and informal saving methods.

<img width="419" height="272" alt="saving_kenya" src="https://github.com/user-attachments/assets/15226cf4-1530-4302-b58d-5adfaa7b5db2" />


# The Changing Landscape of Credit Access

While overall borrowing declined slightly between 2021 and 2024, the source of formal credit changed dramatically.

Informal lending through family, friends, and community Chamas remained the largest source of borrowing, increasing marginally from **36.32% to 37.35%**.

Within the formal financial sector, exclusive mobile money borrowing increased from **17.51% to 24.93%**, while exclusive borrowing from commercial banks fell from **10.05% to 5.18%**. Borrowers using both systems also declined from **12.12% to 7.43%**.

**Key Insight:** Mobile money has emerged as Kenya's preferred formal lending channel, while informal community lending continues to play an essential role alongside digital finance.

<img width="406" height="263" alt="Borrowing_Kenya" src="https://github.com/user-attachments/assets/6f901c03-6248-4959-887e-f5675be8589a" />


# The Digital Transformation of Wage Payments

Mobile money is no longer limited to person-to-person transfers.

Between 2021 and 2024, employers increasingly shifted payroll away from cash and traditional bank transfers toward mobile money.

Cash wage payments declined from **5.88% to 4.95%**, while bank-only salary payments fell from **3.64% to 2.75%**. Over the same period, wages received through mobile money increased from **14.61% to 18.59%**.

**Key Insight:** Mobile money has become an increasingly important payroll channel, reflecting its growing role in both personal finance and business operations.

       <img width="443" height="263" alt="Private_sector_wages" src="https://github.com/user-attachments/assets/a0d9815b-bff8-48ce-9464-2ab9c3032242" />


# The Bigger Picture

Looking across savings, borrowing, and wage payments, one pattern becomes clear.

Kenya's financial progress is no longer defined solely by increasing access to financial services—it is characterized by a shift in how those services are used. Mobile money has evolved from a convenient payment tool into the primary platform through which millions of people save, borrow, receive income, and participate in the formal economy.

Rather than replacing traditional banks, mobile money has reshaped their role, creating a more integrated and digitally connected financial ecosystem.



# Challenges

* Global Findex indicators contain overlapping populations, making direct comparisons misleading.
* Multiple datasets had to be cleaned, standardized, and merged before analysis.
* Several financial indicators required custom calculations using set theory to isolate mutually exclusive groups.
* Missing values and inconsistent naming conventions across downloaded indicators required preprocessing before modeling.
* Ensuring percentages remained logically consistent after removing overlaps was one of the project's biggest analytical challenges.



# Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Wrangling
* Data Integration
* Set Theory Applications
* Statistical Reasoning
* Power BI Dashboard Development
* DAX
* Data Storytelling
* Financial Inclusion Analytics
