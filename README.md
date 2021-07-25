# sales-predictions

# Big Mart Sales Prediction

Sales predictions for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.

Here is the Data Dictionary for this dataset:

Variable Name	Description

Item_Identifier	Unique product ID

Item_Weight	Weight of product

Item_Fat_Content	Whether the product is low fat or regular

Item_Visibility	The percentage of total display area of all products in a store allocated to the particular product

Item_Type	The category to which the product belongs

Item_MRP	Maximum Retail Price (list price) of the product

Outlet_Identifier	Unique store ID

Outlet_Establishment_Year	The year in which store was established

Outlet_Size	The size of the store in terms of ground area covered

Outlet_Location_Type	The type of area in which the store is located

Outlet_Type	Whether the outlet is a grocery store or some sort of supermarket

Item_Outlet_Sales	Sales of the product in the particular store. This is the target variable to be predicted.

# Sources
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

# Part 2

To clean the data Item Fat Content different names were organized. For the missing data in Item Weight the mean weight from the different Item Types were used.
  
# Part 3

A bar graph and pie charts were used to help understand, explain, model the data.![download (14)](https://user-images.githubusercontent.com/37349912/126885257-5547c683-6ce3-4b22-ade2-f280295110a4.png)
![download (15)](https://user-images.githubusercontent.com/37349912/126885258-5686f541-69d2-417b-9e0f-63f2b4451991.png)
![download (16)](https://user-images.githubusercontent.com/37349912/126885271-c11e0f7f-d2f3-4478-8782-5ea3756bc0a8.png)
  
# Part 4

Histograms, boxplots and heatmap were used to help stakeholders better understand trends in the data.
![download (17)](https://user-images.githubusercontent.com/37349912/126885470-9be12e5d-b00e-4fb9-b045-0d41d77da5e3.png)
![download (18)](https://user-images.githubusercontent.com/37349912/126885344-d9ca6ea6-9b46-460d-96f5-9e3340f0c5ae.png)

# Part 5

Linear Regression and KNN models were used to predict sales.



