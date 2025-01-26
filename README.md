Data Science Assignment: eCommerce Transactions Dataset
Overview
This project involves working with an eCommerce Transactions dataset consisting of three files: Customers.csv, Products.csv, and Transactions.csv. 
The goal is to perform exploratory data analysis (EDA), build predictive models, and derive actionable insights that can be valuable for business decision-making.
The assignment evaluates your skills in data analysis, machine learning, and generating business insights.

Dataset Files
Customers.csv

CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.
Products.csv

ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Product price in USD.
Transactions.csv

TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction.
Price: Price of the product sold.
Assignment Tasks
Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform EDA on the provided dataset.
Derive at least 5 business insights from the EDA (maximum 100 words per insight).
Deliverables:

A Jupyter Notebook/Python script containing your EDA code.
A PDF report with business insights (maximum 500 words).
Task 2: Lookalike Model
Build a Lookalike Model that takes a user's information as input and recommends 3 similar customers based on their profile and transaction history. The model should:

Use both customer and product information.
Assign a similarity score to each recommended customer.
Deliverables:

A “Lookalike.csv” file with the top 3 lookalikes and their similarity scores for the first 20 customers.
A Jupyter Notebook/Python script explaining the model development.
Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques, utilizing both customer profile information and transaction data. You can choose any clustering algorithm with 2 to 10 clusters. Evaluate the clustering using DB Index and other relevant metrics.

Deliverables:

A report on your clustering results, including:
Number of clusters.
DB Index value.
Other relevant clustering metrics.
A Jupyter Notebook/Python script containing your clustering code.
Submission Instructions
GitHub Link: Upload all the PDF and code files to a public GitHub repository.
File Naming Convention:
FirstName_LastName_EDA.pdf
FirstName_LastName_EDA.ipynb
FirstName_LastName_Lookalike.csv
FirstName_LastName_Lookalike.ipynb
FirstName_LastName_Clustering.pdf
FirstName_LastName_Clustering.ipynb
Evaluation Criteria
Task Weightage:
Exploratory Data Analysis: 25%
Business Insights: 15%
Lookalike Model: 30%
Customer Segmentation: 30%
