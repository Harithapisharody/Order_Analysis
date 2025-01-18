# Sales Orders EDA Analysis

This repository contains an Exploratory Data Analysis (EDA) on an order details dataset. The goal of this project is to uncover patterns, relationships, and insights within the data through statistical analysis and visualizations. Additionally, the analysis aims to identify which segment has the most profit, enabling the businessman to target and expand sales in that segment.

## Dataset Description

The dataset consists of the following columns:

- **Order_ID**: Unique identifier for each order
- **Order_Date**: The date when the order was placed
- **Ship_Date**: The date when the order was shipped
- **Aging**: The time difference between the order date and the ship date
- **Ship_Mode**: Mode of shipment (e.g., Standard, First Class)
- **Product_Category**: Category of the product ordered
- **Product**: Name of the product ordered
- **Sales**: Sales amount for the product
- **Quantity**: Quantity of the product ordered
- **Discount**: Discount applied to the product
- **Profit**: Profit from the sale of the product
- **Shipping_Cost**: Cost of shipping for the order
- **Order_Priority**: Priority level of the order (e.g., Low, Medium, High)
- **Customer_ID**: Unique identifier for the customer
- **Customer_Name**: Name of the customer
- **Segment**: Customer segment (e.g., Corporate, Home Office, etc.)
- **City**: City where the customer is located
- **State**: State where the customer is located
- **Country**: Country where the customer is located
- **Region**: Region where the customer is located
- **Months**: Month of the order

## EDA Process

The Exploratory Data Analysis (EDA) process includes:

1. **Data Cleaning**: Handling missing values, data types, and outliers.
2. **Summary Statistics**: Descriptive statistics for key variables.
3. **Data Visualization**: Visualizations such as histograms, box plots, and heatmaps to reveal patterns and relationships.
4. **Correlations and Insights**: Identifying correlations between variables to understand business trends.
5. **Segment Profit Analysis**: Identifying which customer segment has the most profit to help businesses expand sales in high-profit segments.

## Files Included

- `Order_Analaysis_EDA.ipynb`: Jupyter Notebook containing the full EDA analysis, visualizations, and insights.
- `Order_Analaysis_EDA.csv`: Raw dataset used for analysis.

## Requirements

To run this analysis, you need the following Python libraries:

- pandas
- matplotlib
- seaborn
- numpy

You can install these libraries using:

```bash
pip install -r requirements.txt
