# New-to-Bank Analysis

# Introduction

In this analysis, we leveraged Power BI to explore, model, and visualize data related to customer transactions, digital penetration, and financial product performance across various branches. The primary goal is to extract actionable insights that will drive business decisions, enhance customer engagement, and optimize product offerings.

## Skills/Concepts Demonstrated
- **DAX (Data Analysis Expressions)**
- **Data Modeling (Star Schema)**
- **Filters and Buttons**
- **Quick Measures**

## Problem Statement
The challenge is to analyze customer transaction behaviors, digital penetration, and product engagement (savings accounts, loans, etc.) to identify opportunities for growth, optimize branch performance, and improve customer experience.

## Data Description/Sourcing
The dataset was provided by the bank, containing customer demographics, transaction records (credit and debit turnover), product engagements (savings goals and loans), and branch performance data. The data spans from January to December 2024 and is structured in multiple tables.

**Number of Rows:** Approximately 50,000 records
- **Number of Columns:** 30 columns
- **Number of Tables:** 4 tables

  ## Data Transformation/Cleaning
- Removal of duplicates and blank records
- Filtering out incomplete or irrelevant entries (e.g., zero credit or debit turnover)
- Data cleansing to ensure consistent formatting (e.g., customer IDs, branch names)

## Data Modeling

The data model follows a **star schema** structure:
- **Fact Table:** Transaction data (credit, debit turnover)
- **Dimension Tables:**
  - Customer demographics
  - Branch details
  - Product details (Loans, Goals)
  - Digital Channels (ALAT, USSD, Cards)
  
The relationships are **one-to-many**, where each dimension table is connected to the fact table.


## Data Analysis and Visuals

1. **Digital Penetration Analysis:**
   - Peak digital penetration in June with 36.1k customers onboarded (334.6% increase).
   - Visual: Line chart showing digital penetration trend over time.
   
2. **Branch Performance:**
   - Egbeda, Dopemu, and Otta branches had the highest customer onboarding and transaction volumes.
   - Visual: Bar chart comparing branch performance.

3. **Product Penetration (Loans and Goals):**
   - 755 customers are on Alat savings goals and loans, with a positive correlation between the two.
   - Visual: Stacked bar chart showing loan and goal penetration across branches.

4. **Clear Balance Growth:**
   - Kaffi Street and Otta branches showed the highest clear balance growth.
   - Visual: Area chart showing clear balance growth by month.

5. **Cross-selling and Up-selling Opportunities:**
   - Tier 1 savings accounts dominate in densely populated areas, while more specialized products underperform in less active regions.
   - Visual: Scatter plot showing product penetration by region.
  
     # Visualization

     ## Digital Penetration


   # Conclusion
The analysis revealed that digital penetration, customer transaction behaviors, and product performance varied significantly across branches. High-performing branches like Egbeda and Dopemu can serve as benchmarks for others, while products like Tier 1 savings and business accounts show strong engagement.

# Recommendations

- Focus on digital channels: Target underperforming branches with marketing strategies to increase digital adoption (e.g., ALAT and USSD).
- Branch-specific strategies: Tailor product offerings based on branch location demographics to maximize customer engagement.
- Enhance cross-selling efforts: Leverage the correlation between loan and goal penetration to upsell complementary products in high-penetration branches.
- Monitor clear balance trends: Focus on branches with declining clear balances and introduce incentives to boost customer retention.
- Target dormant products: Boost promotion of underperforming products like prepaid cards and FGN-wallet to balance product engagement across all branches.

