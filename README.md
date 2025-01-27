# 💳 Credit Card Customer Clustering Project

## 🎯 Aim
The primary aim of this project is to **cluster credit card customers** based on their financial behavior and transaction patterns. By analyzing and grouping customers, this project seeks to:
- Uncover distinct customer segments.
- Enable businesses to tailor marketing strategies.
- Optimize credit limits and improve customer retention.

The clustering approach provides valuable insights into customer behavior, enabling **data-driven decision-making** in the financial domain.

---

## 📊 Dataset Overview
The dataset consists of **17 features** that describe the financial activities and attributes of credit card customers. Below are the key features:

- **CUST_ID**: Unique identification number of the customer.
- **BALANCE**: Current balance in the customer's bank account.
- **BALANCE_FREQUENCY**: How frequently the balance is updated (1 = frequently, 0 = rarely).
- **PURCHASES**: Total amount of purchases made by the customer.
- **ONEOFF_PURCHASES**: Highest amount spent on a single purchase.
- **INSTALLMENTS_PURCHASES**: Total amount spent on installment purchases.
- **CASH_ADVANCE**: Total cash advanced by the customer.
- **PURCHASES_FREQUENCY**: Frequency of purchases (1 = high, 0 = low).
- **ONEOFF_PURCHASES_FREQUENCY**: Frequency of one-time purchases (1 = high, 0 = low).
- **PURCHASES_INSTALLMENTS_FREQUENCY**: Frequency of installment purchases (1 = high, 0 = low).
- **CASH_ADVANCE_FREQUENCY**: Frequency of cash advances (1 = high, 0 = low).
- **CASH_ADVANCE_TRX**: Number of cash advance transactions.
- **PURCHASES_TRX**: Total number of purchase transactions.
- **CREDIT_LIMIT**: Credit limit assigned to the customer.
- **PAYMENTS**: Total amount of payments made by the customer.
- **MINIMUM_PAYMENTS**: Minimum amount paid by the customer.
- **PRC_FULL_PAYMENT**: Percentage of payments made in full.
- **TENURE**: Number of months the customer has been using the credit card.

---

## 📈 Cluster Distribution
The dataset was clustered into **7 distinct groups**, with the following distribution:

| Cluster | Members | Notes |
|---------|---------|-------|
| **0**   | 5102    | Largest cluster; minimal activity. |
| **5**   | 1736    | Moderate activity and spending. |
| **6**   | 1048    | Moderate activity with varying balances. |
| **1**   | 481     | High-value customers with significant balances. |
| **2**   | 208     | Medium activity and spending. |
| **4**   | 37      | Niche group with unique patterns. |
| **3**   | 24      | Smallest cluster; high-value, high-spending customers. |

---

## 🚀 Technologies Used
- **Python** 🐍
- **Jupyter Notebook** 📓
- **Plotly** 📊
- **Scikit-Learn** 🤖
- **Pandas & NumPy** 📚

---
