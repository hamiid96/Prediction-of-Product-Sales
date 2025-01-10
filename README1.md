# Prediction of Product Sales 
## Analysis Procedure
In this project, we wnat to predict the Item Outlet Sales for four different stores in this state. The overall objective of this data analysis is to create a model that can predict the food item sales for these stores and improve food item sales accordingly. To do so, we have checked the relationships between all features in the attached dataset as following. 
**Author**: Abdulhamid Abuzarour
### Business Objective
The esteemed goal of this project is to help the retaliler to understand the properties of products and outlets that play crucial roles in increasing sales. 
### Data
The dataset features in this project consists of three main types:Nominal, Ordinal and Numerical features. These features are related to the retailer target for predicting food item sales. 
### Exploratory Data Analysis 
#### Relationships in Numeric Features using the Heatmap
![image](https://github.com/user-attachments/assets/82373996-8a2f-4e55-9aeb-f04d0478a58b)

Based on the heatmap above, It has been noticed the only numeric feature can influence the target is "Item_MRP"

-------------------------------------------------

#### Outlet Size Vs. Item Outlet Sales
![image](https://github.com/user-attachments/assets/34d7b98a-79fb-4bb4-8f04-1caf64aafa3e)

Depending on the figure above, I can say that the Outlet Size can influence the Item Outlet Sales. The medium size of outlets achieves the high sales 

## Final Model 
1.   Overall, I can choose the Linear Regression model due to this model learned enough from the training data and shows fair-enough results in the testing data with a slight difference between R2 values. However, this model still not well-fitted model because of relatively low R2 values. So, this model needs more improvement.

2.   Regarding the MAE values in the Random Forests model after tuning, the training data shows better values than testing data. Testing data has a plus-minus error of 819$ within the mean value which indicates a high value of error based on items prices. In other words, the MAE value in testing data has +- 37% error from the mean value, and this error is not acceptable for item prices.

## Recommendations 
1. Depending on the selected model which achieved unsatisfied results, I recommend to use other deep learning processes like Feature Engineering and Nueral Networks models.
