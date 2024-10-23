# Danny_Ma_4th_Case
Databank Data Analysis

🏦 8-Week SQL Challenge: Case Study #4 - Data Bank
Project Overview
Welcome to my analysis of Danny Ma's 4th case study, the Data Bank challenge, from the 8-Week SQL Challenge. This case study simulates a customer banking environment, focusing on understanding customer nodes, transactions, and experimenting with different data allocation methods to estimate how much data would be required for various strategies.

The aim of this project is to provide a detailed analysis of customer data patterns and test multiple hypotheses for data allocation, along with key insights into how to manage resources efficiently.

Key Analytical Objectives
The analysis is broken down into three main areas:

Customer Nodes Exploration
Customer Transactions Analysis

Data Allocation Experimentation
1. Customer Nodes Exploration
This section focuses on understanding the distribution of nodes across regions and customer reallocation patterns.

Key Insights:
Unique Nodes: There are X unique nodes in the Data Bank system, supporting the banking operations across different regions.
Nodes per Region: Region A has the highest number of nodes with X nodes, while Region B has the least with Y nodes.
Customer Reallocation: On average, customers are reallocated to different nodes every Z days. The median reallocation time is X days, with the 80th percentile at Y days and the 95th percentile at Z days.
These reallocation patterns highlight the efficiency of the Data Bank system in managing node resources and customer migrations.

2. Customer Transactions
The customer transaction analysis examines transaction types, historical deposit patterns, and customer behavior in terms of deposits, purchases, and withdrawals.

Key Insights:
Transaction Types: There are X unique transaction types with a total transaction value of $Y. The most frequent transaction type is deposits, while withdrawals account for the highest value in transactions.
Deposit Patterns: On average, customers have X deposits historically, totaling $Y in deposit amounts.
Monthly Activity: Z% of customers make more than one deposit and at least one purchase or withdrawal in any given month, indicating a high level of customer engagement and transactional activity.

3. Data Allocation Experimentation
Three data allocation strategies were tested to determine how much data the Data Bank would need to provision for each option:

Option 1: Data is allocated based on the closing balance at the end of the previous month.
Option 2: Data is allocated based on the average balance over the past 30 days.
Option 3: Data is updated in real-time.

Key Insights:
Monthly Data Requirements: The analysis showed that Option 3 (real-time data updates) would require the most data, while Option 1 (based on previous month’s balance) was the most efficient in terms of data usage.
This finding can help Data Bank optimize its data provisioning strategy, balancing performance with resource efficiency.

4. Extra Challenge: Data Growth with Interest
In this challenge, an interest-based data allocation model was explored, where customers’ data grows at a 6% annual interest rate calculated daily. Two models were tested:

Non-compounding interest
Compounding interest

Key Insights:
Data Growth: The non-compounding interest model resulted in a more predictable data growth, while the compounding model provided faster growth but would require more data resources to manage.

Conclusion
This project provided an in-depth analysis of customer nodes, transaction patterns, and data allocation strategies for the Data Bank system. The insights gained can help Data Bank optimize their data allocation, ensuring that they provide adequate resources while minimizing waste. The interest-based allocation model further demonstrates a unique approach to incentivizing customers while managing data provisioning effectively.

Repository Structure
Kodu kopyala
📂 DataBank-CaseStudy4/
   ├── 📁 Analysis
   │   └── customer_nodes_analysis.sql
   │   └── transaction_analysis.sql
   │   └── data_allocation.sql
   ├── 📁 Data
   │   └── nodes_data.csv
   │   └── transactions_data.csv
   ├── 📄 README.md
   └── 📄 Summary_Report.pdf

How to Run
Clone the repository:
git clone https://github.com/your-repo/DataBank-CaseStudy4.git
Load the datasets and run the SQL queries in your preferred database environment.
