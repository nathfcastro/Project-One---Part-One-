# Sales Predictions 
Nathalie Castro 
## Overview: 
The objective of this project is to anazlyze the past sales data and establish connections that will confidently develop future sales and assist the company to endorse better financial decisions. 

## Below is the dictionary for the analyzed dataset: 

![image](https://user-images.githubusercontent.com/122195358/225798639-22a9086f-4b21-404f-8ee0-5bcd5c490b1e.png)

## Data Cleaning 
During the data cleaning and analyzing, I identified missing and duplicating values that were then dropped or replaced in the data set. This was done to get cleaner data to work with for the exploratory and explanatory visuals. 

## Exploratory Visuals
During this stage, I created a Correlation Heatmap that establishes connections between the different data. Below you can see the darker the color is the more established correlation we have between the data sets. Example, the Item_MRP is heavily correlated with the Item_Outlet_Sales.

![image](https://user-images.githubusercontent.com/122195358/225799805-a9e066dc-31c7-4509-bccf-72b810a96c2b.png)

## Explanotry Visuals 
Using the Correlation Heatmap, we didn't get to understand the correlation between the item type and the sale price of that item. We want to ensure that we establish the connection between prices to distinguish how can companies price these that create knowledge of better financial decisions. Below you will visually understand which items cost the most and least amount of money.

![image](https://user-images.githubusercontent.com/122195358/225805576-a3def6a5-b55c-4a00-84cc-1f6aaa9829c7.png)

The visual above gives us more information about the item types that cost the most and the least. 

The top five highest outlet priced items are as follows: 

*   Starchy Foods
*   Seafood 
* Fruits and Vegetables
* Snack Foods
* Household Items

The bottom five lowest outlet priced iems are as followed: 

* Breakfast 
* Health and Hygiene 
* Soft Drinks 
* Baking Goods 
* Others

## Model & Metrics
To determine predicted sales, I used Linear and Decision Tree Regression. Below are the error metrics: 

* **Linear Regression**
> ![image](https://user-images.githubusercontent.com/122195358/225803320-fd82e167-bad6-40fd-9b84-a7fb5baddc9b.png)

* **Decision Tree Regression**  
> ![image](https://user-images.githubusercontent.com/122195358/225803414-40c47a5f-02a6-4042-bcaa-e78a9456cc7a.png)

The metrics above depict that the Decision Tree Regression was the best out of the two. When reading these metrics we want a high R2 and low MAE, MSE, and RMSE in our tested results comapred to the train results. When we compare the MAE, MSE, and RMSE we can see these scores are comparatively lower on the test scores than the train scores. This then states that it has a lower bias and lower variation compared to the Linear Regression metric. 

# Final Recommendations
I recommend we find the correlation between the items that are more visible and items that cost more to buy rather than to sell. We want our sales to go up and not break even. Since our highest outlet priced foods were: Starchy Foods, Seafood, Fruits and Vegetables, Snack Foods, and Household Items we can focus on purchasing these items in wholesale for a lower price per say. Additionally, when predicting our metrics I would say using Decision Tree was the best way to predict for now. However, I would reccomend to use other methods to get a better understanding. 
