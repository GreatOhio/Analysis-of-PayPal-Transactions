# Analysis-of-PayPal-Transactions
1. Project Overview:
This project analyzes a dataset of PayPal transactions to uncover insights into financial activities. It explores different types of transactions, customer behaviors, and potential fraudulent activities. By leveraging data analysis techniques, the project aims to provide a clearer understanding of transaction trends, success rates, and regional transaction distributions.

2. Problem Statement:
With the growing number of digital transactions, it becomes increasingly important to detect fraudulent activities, optimize payment processes, and understand customer transaction behaviors. This project addresses key challenges such as:

            Identifying patterns in successful and unsuccessful transactions.
            
            Detecting anomalies that might indicate fraudulent transactions.
            
            Analyzing transaction trends across different regions, platforms, and payment types.
            
            Providing actionable insights to improve financial decision-making.

3. Data Source:
The dataset, "Paypal_Transactions3.csv", contains 200 transaction records with the following key fields:
        
            Transaction ID – A unique identifier for each transaction.
            
            Type – The nature of the transaction (e.g., Charge, Refund).
            
            Transaction Type – Categorization into "Goods and Services" or "Friends & Family".
            
            Customer Name – The name of the customer involved.
            
            Total – The transaction amount.
            
            Success – Whether the transaction was successful (1) or not (0).
            
            Day – The date of the transaction.
            
            Transaction Notes – Additional details about the transaction.
            
            Source – The platform used for the transaction (Tablet, Phone, Desktop).
            
            Country – The country where the transaction originated.
            
            Auth Code – A unique authorization code for security purposes.
            
4. Methodology (Tools, Techniques, and Process Used)
Tools Used:
            Python libraries: pandas, numpy, and datetime
            Jupyter Notebook for data analysis and visualization
            CSV file processing using pandas
            Techniques & Process:
            Data Loading & Cleaning

The dataset is loaded using pandas.read_csv().
Irrelevant columns like "Transaction_ID" and "Auth_code" are dropped.
Missing values in "Transaction_Notes" are filled with "N/A".
The "Day" column is converted into a datetime format.
Data Exploration & Transformation

The project analyzes successful transactions only (Success == 1).
Transaction trends over time are examined using .max() and .min().
Categorical values like "Type", "Transaction_Type", "Country", and "Source" are analyzed for trends.
Statistical Analysis & Insights Extraction

Summary statistics are calculated using .describe().
The distribution of transaction types, sources, and country-based transactions is analyzed.




















