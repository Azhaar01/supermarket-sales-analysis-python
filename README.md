# Supermarket Sales Analysis using Python

This repository contains a data analysis project on supermarket sales. The goal is to analyze and visualize sales data to uncover valuable insights such as peak sales hours, most profitable branches, and customer behavior. The analysis is done using Python and popular data science libraries.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Analysis Steps](#analysis-steps)
4. [Technologies Used](#technologies-used)
5. [Summary](#summary)

---

## Introduction

Supermarkets generate large amounts of data from their daily transactions. Analyzing this data helps businesses understand customer preferences, improve sales strategies, and optimize operations. This project analyzes the sales data of a supermarket to answer key business questions.

## Dataset

The dataset used in this project contains the following columns:

- **Invoice ID**: Unique identifier for each sale.
- **Branch**: The branch where the transaction took place (A, B, C).
- **City**: The city where the supermarket branch is located.
- **Customer type**: Type of customer (Member or Regular).
- **Gender**: Gender of the customer.
- **Product line**: The category of products sold (e.g., Food and Beverages, Health and Beauty).
- **Unit price**: Price per unit of the product.
- **Quantity**: Quantity of the product sold.
- **Tax 5%**: Tax applied to the transaction.
- **Total**: Total sales amount (including tax).
- **Date**: Date of the transaction.
- **Time**: Time of the transaction.
- **Payment**: The method of payment used by the customer (e.g., Ewallet, Cash).
- **COGS (Cost of Goods Sold)**: The cost of the products sold.
- **Gross margin percentage**: The margin percentage for the products sold.
- **Gross income**: Gross income from the transaction.
- **Rating**: Customer satisfaction rating.

## Analysis Steps

1. **Data Cleaning**:
    - Ensured there were no missing values in the dataset.
    - Converted data types (e.g., parsing dates and times correctly).

2. **Branch Performance Analysis**:
    - Calculated total sales for each branch.

3. **Product Line Analysis**:
    - Analyzed total sales by product line.

4. **Customer Type Analysis**:
    - Compared spending patterns between members and regular customers.

5. **Gender-based Analysis**:
    - Identified the most frequently ordered products by gender.

6. **Peak Hour Identification**:
    - Identified the hour with the highest total sales.

7. **Payment Method Analysis**:
    - Determined the most used payment method across different cities and branches.

8. **Customer Rating Analysis**:
    - Compared average ratings for each branch.

9. **Sales Movement Analysis**:
    - Compared sales trends across different branches.

## Technologies Used

- **Python**: Programming language for data analysis.
- **Pandas**: Data manipulation library.
- **Matplotlib & Seaborn**: Visualization libraries for static plots.
- **Plotly**: For interactive visualizations.

## Summary

- **Branch with the highest total sales**: Branch C.
- **Most profitable product line**: Food and Beverages.
- **Customer spending**: Members spend 3.45% more than regular customers, indicating a stronger loyalty effect.
- **Top-selling products by gender**:
    - Female customers: Most frequently ordered "Food and Beverages," generating sales of 33,170.92.
    - Male customers: Most frequently ordered "Health and Beauty," generating sales of 30,632.75.
- **Peak sales hour**: 7 PM, with total sales of 39,699.51.
- **Most used payment method**: Ewallet, with 345 uses, primarily in Branch C and the city of Yangon.
- **Customer ratings**: Branch C has the highest rating, with a score of 7.07.
- **Sales movement**: Branch C has the highest sales movement, while Branch A shows less variation.

