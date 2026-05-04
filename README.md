# Online Retail Sales Analysis  & Customer Insight Using Python

## Project Overview
This project focuses on analyzing a real-world e-commerce dataset to uncover meaningful insights about sales performance, customer behavior, and product demand.

The dataset contains transactional data from an online retail store, including product details, quantities purchased, pricing, and customer locations.

## Objective
The goal of this project is to:
- Clean and preprocess raw transactional data
- Handle missing values and duplicates
- Remove invalid transactions
- Perform exploratory data analysis (EDA)
- Generate insights from sales patterns
- Visualize key trends

## Data Cleaning Process
To ensure data quality and reliability, the following steps were carried out:
- Removed missing values in critical fields (CustomerID)
- Eliminated duplicate records
- Filtered out negative quantities (returns/refunds)
- Ensured consistency in data types

## Feature Engineering
A new feature was created to enhance analysis:

- **TotalPrice** = Quantity × UnitPrice  
This represents the total value of each transaction.

## Exploratory Data Analysis
The dataset was analyzed to answer key questions such as:
- What are the top-selling products?
- Which countries generate the most orders?
- What is the total revenue generated?

## Data Visualization
Basic visualizations were created to highlight:
- Top countries by number of orders
- Distribution of transactions

## Tools and Technologies
- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

## Key Insights
- Certain countries contribute significantly more to total orders
- A small number of products dominate sales volume
- Data cleaning significantly improved the reliability of results

## Project Structure 
online-retail-analysis/
│
├── online_retail_analysis.ipynb # Main analysis notebook
├── README.md # Project documentation

## Future Improvements
- Build interactive dashboards (Power BI / Tableau)
- Perform time-series analysis on sales trends
- Apply predictive modeling for sales forecasting

## Author [Temidare]
This project was completed as part of a data analytics learning journey, focusing on building real-world problem-solving skills using Python.

I am open to entry-level data analysis opportunities, collaborations, and learning experiences.
