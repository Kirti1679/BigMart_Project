<!-- # BigMart_Project -->
# Big Mart Sales Prediction

## 📝 Project Overview

This project aims to predict the sales of products in various Big Mart outlets. The goal is to build a machine learning model that can accurately forecast sales based on a product's and outlet's attributes. This can help Big Mart optimize inventory management, understand customer behavior, and make better business decisions.

The analysis, data preprocessing, and model training are all contained within the `BigMart_Project.ipynb` Jupyter Notebook.


# Dataset

The dataset is provided in two files: Train.csv and Test.csv. It contains 12 variables, including product details, outlet information, and the target variable, Item_Outlet_Sales.

**Key Features:**
* **Item_Identifier:** Unique product ID
* **Item_Weight:** Weight of the product
* **Item_Fat_Content:** Fat content of the product
* **Item_Visibility:** The percentage of total display area of all products in a store allocated to the particular product
* **Item_Type:** The category to which the product belongs
* **Item_MRP:** Maximum Retail Price (list price) of the product
* **Outlet_Identifier:** Unique store ID
* **Outlet_Establishment_Year:** The year in which store was established
* **Outlet_Size:** The size of the store in terms of ground area covered
* **Outlet_Location_Type:** The type of city in which the store is located
* **Outlet_Type:** Whether the outlet is just a grocery store or some sort of supermarket
* **Item_Outlet_Sales:** The sales of the product in the particular store (This is the target variable to be predicted).
