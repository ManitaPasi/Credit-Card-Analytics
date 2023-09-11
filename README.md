# SQL Portfolio Project: Analyzing Credit Card Spending Habits in India

Welcome to the SQL Portfolio Project. In this project, we will be exploring a dataset on credit card transactions to gain insights into spending habits in India.

## Table of Contents
- [Getting Started](#getting-started)
  - [Download the Dataset](#download-the-dataset)
  - [Import the Dataset](#import-the-dataset)
- [Exploration and Analysis](#exploration-and-analysis)
  - [Sample Queries](#sample-queries)
- [Project Completion](#project-completion)

## Getting Started

### Download the Dataset

- Download the credit card transactions dataset from this [Kaggle link](https://www.kaggle.com/datasets/thedevastator/analyzing-credit-card-spending-habits-in-india).
  
  **Note**: Alternatively, you can use the dataset provided in the zip file if available.

### Import the Dataset

1. Import the dataset into your SQL server using the table name: `credit_card_transactions`.
2. Convert all column names to lowercase before importing.
3. Replace spaces within column names with underscores (e.g., "Credit Card" should be renamed to "credit_card").
4. While importing, adjust the data types of columns, as they might be defaulted to varchar.

## Exploration and Analysis

After setting up the dataset, you can begin exploring and deriving insights from it.

### Sample Queries:

1. **Top Spending Cities**: Extract the top 5 cities with the highest credit card spends and their percentage contribution of the total.
2. **Spending by Card Type**: Identify which month experienced the highest spend for each card type and the respective amount spent.
3. **Transaction Milestone**: Retrieve transaction details where cumulative spending for each card type reached 1,000,000.
4. **Gold Card Analysis**: Identify the city that recorded the lowest percentage spend for the gold card type.
5. **Expense Type Highlights**: For each city, pinpoint the highest and lowest expense types.
6. **Female Spending Habits**: Determine the percentage contribution of spending by females across various expense categories.
7. **Growth Analysis**: Establish which card and expense type combination showed the most significant month-over-month growth in Jan-2014.
8. **Weekend Spend Analysis**: Find out which city has the highest spend-to-transaction count ratio over weekends.
9. **Time to 500 Transactions**: Determine the city that reached its 500th transaction in the shortest time post its inaugural transaction.

## Project Completion

Upon concluding your analyses:

1. Consolidate and present your findings.
2. Initiate a GitHub repository to host your SQL scripts and insights.
3. Ensure your GitHub repository includes a comprehensive README detailing your procedures, queries, and outcomes.

### Example GitHub Repositories for Inspiration:

- [SQL Data Analysis and Visualization Projects](https://github.com/ptyadana/SQL-Data-Analysis-and-Visualization-Projects/tree/master/Advanced%20SQL%20for%20Application%20Development)
- [COVID Portfolio Project](https://github.com/AlexTheAnalyst/PortfolioProjects/blob/main/COVID%20Portfolio%20Project%20-%20Data%20Exploration.sql)

Happy Analyzing! 📊🔍
