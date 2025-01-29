# Identifying Shopping Trends using Data Analysis

## Overview
This project explores an EDA (Exploratory Data Analysis) on the **Online Sales Dataset**, which is available on Kaggle. The dataset contains information related to customer purchases, including product details, quantity, unit price, discount, and customer-specific data.

In this project, various patterns and trends related to shopping behaviors are identified, such as:
- How customer spending varies with discount status
- Distribution of order priorities
- Seasonal trends in customer purchases
- Purchase behavior by payment method and more

The goal is to uncover valuable insights from the dataset that could be useful for business analysis, marketing strategies, and customer behavior prediction.

## Dataset
The dataset used for this analysis is the **Online Sales Dataset** by Yusuf Delikkaya, available on Kaggle. You can find the dataset here:  
[Online Sales Dataset - Kaggle](https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset)

The dataset includes the following columns:
- `InvoiceNo`: Unique identifier for each invoice
- `StockCode`: Unique product code
- `Description`: Description of the purchased product
- `Quantity`: Number of units purchased
- `InvoiceDate`: Date and time of the purchase
- `UnitPrice`: Price per unit of the purchased item
- `CustomerID`: Unique identifier for each customer
- `Country`: Country where the purchase was made
- `Discount`: Discount applied to the purchase
- `PaymentMethod`: Customer's preferred payment method
- `ShippingCost`: Cost of shipping for the order
- `Category`: Product category
- `SalesChannel`: Whether the purchase was made online or in-store
- `ReturnStatus`: Whether the item was returned or not
- `ShipmentProvider`: Logistics provider
- `WarehouseLocation`: Warehouse location
- `OrderPriority`: Priority level of the order (High, Medium, Low)

## Requirements

Before running the notebook, make sure to have the following libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `IPython`

To install these dependencies, run the following command:

```bash
pip install pandas numpy matplotlib seaborn plotly ipython
