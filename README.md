# Bank-Statement Analysis

This is an end-to-end project where I analyzed my personal bank account statement to understand financial patterns and trends over a set period.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](https://github.com/Debido1/Bank-Statement/blob/main/Account%20cleaned.xlsx)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into personal financial patterns by analyzing bank account transactions over a specific period. By examining the account statement data, the project seeks to uncover spending habits, identify monthly trends, and provide a clearer view of income versus expenses. The goal is to make data-driven observations and recommendations for better financial management and budgeting.

![acc](https://github.com/user-attachments/assets/de54be1e-24bc-4378-8f56-d5cf53e5283e)


### Data Sources

Bank Statement: The primary dataset used for this analysis is the "Account cleaned.xlsx" file, containing detailed information about each transaction made for a specific period of time.

### Tools

- Excel - Creating Reports
- Python - Data Cleaning and Data Analysis


### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- What is the overall income versus expense trend?
- Which types of transactions (like transfers, ATM withdrawals, etc.) are most common?
- Are there specific months with higher spending or income?

### Data Analysis

Include some interesting code/features worked with

- **Monthly Extraction**: Used code to extract the month from each transaction date, allowing for monthly trend analysis.
- **Summing Credit and Debit Columns**: Calculated the total income and total expenses by summing credit and debit columns, providing a clear view of financial activity.
- **Remaining Balance Calculation**: Computed the remaining balance by calculating the difference between total income and expenses, offering insight into overall financial health.

### Results/Findings

The analysis results are summarized as follows:

1. **Credit Summary**: Total credits over 5 months amount to ₦1,165,090.90, indicating total incoming funds.

2. **Debit Summary**: Total debits over 5 months amount are ₦1,165,091.05, indicating total outgoing funds.

3. **Balance**: The remaining balance is ₦0.15, which implies that debits closely match credits, leaving a nearly zero balance.

4. **Debit per Channel**: The E-Channel is the primary channel for debit transactions, with minimal use of ATM, POS, and USD channels.

5. **Credit per Channel**: The E-Channel also leads in credit transactions, with other channels contributing little to overall credit values.

6. **Credit per Month**: There’s a spike in credit transactions during the month of August, suggesting a peak in income.

7. **Debit per Month**: Similarly, debits also peak in the same month as credits, indicating increased spending when income is higher.

   
### Recommendations

Based on the analysis, we recommend the following actions:
- **Monitor Spending**: Since debits closely follow credits, tracking expenses might help in identifying areas where spending could be reduced.
- **Savings Strategy**: Given the nearly zero balance, consider implementing a savings plan, especially after months with high income.
- **Diversify Transaction Channels**: Since the E-Channel is heavily relied on, exploring other channels (such as POS or ATM for cash withdrawals) could provide flexibility in managing transactions.
