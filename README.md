# Customer_Segmentation

Libraries Used
pandas

numpy

matplotlib

seaborn

scikit-learn

Customer Segmentation Analysis
This repository contains a Jupyter Notebook for customer segmentation analysis. The project aims to group customers into different segments based on their demographic information, purchasing habits, and responses to marketing campaigns. This helps in understanding customer behavior and tailoring marketing strategies for different segments.

Dataset
The analysis is performed on a dataset named customer segmentation.csv. The dataset contains information about customers, including:

ID: Unique identifier for each customer

Year_Birth: Customer's birth year

Education: Customer's education level

Marital_Status: Customer's marital status

Income: Customer's yearly household income

Kidhome: Number of children in the household

Teenhome: Number of teenagers in the household

Dt_Customer: Date of customer's enrollment with the company

Recency: Number of days since the last purchase

MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds: Amount spent on different product categories in the last 2 years

NumDealsPurchases: Number of purchases made with a discount

NumWebPurchases, NumCatalogPurchases, NumStorePurchases: Number of purchases made through different channels

NumWebVisitsMonth: Number of visits to the company’s website in the last month

AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5: 1 if the customer accepted the offer in the respective marketing campaign, 0 otherwise

Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

Analysis
The Jupyter Notebook Customer_Segmentation.ipynb includes the following steps:

Data Loading and Exploration: The dataset is loaded, and initial exploratory data analysis is performed to understand the data's structure and features.

Data Cleaning:

Handling missing values in the Income column.

Removing irrelevant columns (Z_CostContact, Z_Revenue).

Feature engineering by extracting day, month, and year from the Dt_Customer column.

Consolidating categories in the Marital_Status column.

Data Visualization:

Bar charts are created to visualize the distribution of categorical features.

A heatmap is generated to show the correlation between different numerical features.

Data Preprocessing: Categorical features are converted to numerical format using Label Encoding to prepare the data for machine learning models.
