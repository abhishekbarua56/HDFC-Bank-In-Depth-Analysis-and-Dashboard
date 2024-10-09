# HDFC-Bank-In-Depth-Analysis-and-Dashboard

This repository contains the Power BI dashboard for HDFC Bank, providing a detailed analysis of banking transactions, account balances, loan amounts, and customer credit scores. The dashboard is designed to offer insights into the bank's performance across different branches, transaction types, and customer demographics.

HDFC Bank Dashboard
Key Features

    Transaction Count: Displays the total number of transactions.
    Total Balance: Shows the overall account balance across all account types.
    Total Loan Amount: Illustrates the total loan amount disbursed by the bank.
    Average Interest Rate: Calculates the average interest rate across all loan accounts.
    Average Credit Score: Provides the average credit score of all customers.

Part 1: Data Cleaning, Modeling, and DAX in Power BI

    Data Importing and Initial Examination:
        Imported datasets into Power BI and performed a preliminary examination.
        Identified data quality issues and inconsistencies.

    Merging and Relating Datasets:
        Merged the datasets using a common key.
        Ensured accuracy in the merge while retaining necessary information.

    Cleaning: Handling Missing and Irrelevant Data:
        Handled missing data, duplicate entries, and irrelevant data points.

    Data Type Conversion:
        Converted and normalized data for consistency across datasets.

    Categorizing Transaction Types:
        Created new columns categorizing transactions based on 'TransactionType'.

    Analysis of Account Balances:
        Calculated average account balances for each account type.

    Currency Exchange Rate Impact:
        Analyzed the effect of currency exchange rates on transaction amounts.

    Branch Activity Analysis:
        Identified which branch (via 'BranchCode') had the highest number of transactions.

    Interest Rate and Balance Correlation:
        Analyzed the correlation between interest rates and account balances using DAX.

    Loan Amount and Credit Score Relation:
        Examined the relationship between loan amount and credit score.

    Transaction Trends Over Time:
        Analyzed transaction trends and identified any seasonal patterns.

    Customer Loyalty Analysis:
        Calculated customer tenure from account opening to the most recent transaction.

    High-Value Transaction Analysis:
        Identified and analyzed high-value transactions.

    Analysis of Transaction Time Patterns:
        Investigated patterns based on the time of day for different transactions.

    Credit Score Distribution:
        Analyzed the distribution of credit scores among customers.

    Correlation Between Account Age and Balance:
        Explored the correlation between account age and balance.

    Performance Rating of Branches:
        Rated branches based on transaction volume and value.

    Extracting Key Information:
        Created new columns for employment sector, years at current residence, and city from 'AccountHolderDetails'.

    Advanced DAX: Risk Assessment Model:
        Developed a risk assessment model using transaction patterns, balances, and credit scores.

    Customer Demographics and Transaction Behavior:
        Analyzed transaction behavior based on customer demographics.

    Branch and Account Type Influence on Transactions:
        Investigated how branches and account types influenced transaction values.

    Predictive Modeling for Account Growth:
        Created a predictive model estimating future account growth using DAX.

    Data Modeling: Time Series Forecasting of Transactions:
        Performed time series forecasting of transaction volumes.

    Advanced Data Transformation: Identifying Unusual Transactions:
        Used Power BI to identify unusual transactions based on transaction types and values.
