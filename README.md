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
```

## How to Run the Project

**Option 1**: Running on Jupyter Notebook
Download the notebook file online_sales_eda.ipynb from this repository.
Open Jupyter Notebook.
Navigate to the directory where the notebook is saved and open the file.
Make sure the dataset Online Sales Dataset is available locally or upload it to the same directory where the notebook is stored.
Run the notebook by executing the cells.


**Option 2**: Running on Google Colab
Open Google Colab (https://colab.research.google.com).
In Colab, go to File > Open notebook > GitHub tab.
Paste the URL of this repository and open the online_sales_eda.ipynb file.
Make sure to upload the dataset to Colab (you can either use files.upload() or mount Google Drive).
Execute the cells to run the EDA.

**Option 3**: Running Locally
1.Clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/Identifying-Shopping-Trends-EDA.git
```
2.Navigate to the project directory:
```bash
cd Identifying-Shopping-Trends-EDA
```
3.Ensure that you have installed all the necessary libraries (mentioned in the requirements section).
4.Run the notebook on Jupyter Notebook or any IDE that supports Python and Jupyter notebooks.

## Key Insights
The notebook will generate various analyses and visualizations, such as:

Distribution of order priorities (High, Medium, Low)
Spending behavior based on discounts
Trends by payment methods, shipping cost, and other customer data
Most frequently purchased products and seasonal trends

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions, please feel free to contact me at [hey.harshgopal@gmail.com].

