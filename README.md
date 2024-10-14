# Customer-Segmentation
This project demonstrates how to perform customer segmentation using transactional data from an online retail store. Customer segmentation helps businesses understand different customer profiles and improve their marketing strategies by grouping customers based on their behavior.

## Table of Contents
- [Project Overview](#Project-Overview)
- [Dataset](#Dataset)
- [Data Cleaning and Preprocessing](#Data-Cleaning-and-Preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)


## Project Overview
The problem statement is
A retailer requires to create customer clusters, which are "customer segments" through a data-driven approach. Currently, the retailer simply groups their international customers by country which is very inefficient way of segmentation. They have provided a dataset of past transaction-level purchase data, aiming to segment customers based on buying patterns.

The goal of this project is to cluster customers based on their purchasing behavior using unsupervised machine learning techniques. Using clustering algorithms such as K-Means to group customers into different segments based on key features derived from their transactional data, where the clustering model factors in both aggregate sales patterns and specific items purchased.


## Dataset
The dataset has 35116 observations for previous international transactions.
The observations span 37 different countries.

We have the following features:

Invoice information

- 'InvoiceNo' – Unique ID for invoice
- 'InvoiceDate' – Invoice date

Item information

- 'StockCode' – Unique ID for item
- 'Description' – Text description for item
- 'Quantity' – Units per pack for item
- 'UnitPrice' – Price per unit in GBP

Customer information

- 'CustomerID' – Unique ID for customer
- 'Country' – Country of customer
