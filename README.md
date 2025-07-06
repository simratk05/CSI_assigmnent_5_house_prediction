# CSI_assigmnent_5_house_prediction
This repository is for the internship program of Celebal data-science internship, in which we had to do EDA on house prediction data set available on Kaggle, 

URL = https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

I made a Kaggle notebbok, which i have uploaded here also

URL = https://www.kaggle.com/code/simratk/simrat-csi-assignment

in this, I have done EDA, 
1- Plot showing count to N/A values in each feature.

![image](https://github.com/user-attachments/assets/31d6a5b9-5b7d-4c2b-981e-1f85f0b254d9)

2- Heat map showing Co-relation between target column and other columns 

![image](https://github.com/user-attachments/assets/945c732a-2262-4d6d-b8b5-0f4342171cc0)

3- Relationship of SalePrice with top features-

The graph illustrates a strong positive correlation between OverallQual and SalePrice, indicating that higher quality homes tend to sell for higher prices. This highlights OverallQual as a key feature influencing house prices in the dataset.
![image](https://github.com/user-attachments/assets/42a5ebca-f8d3-4a9d-bb47-18755ab7bae5)


This graph shows a clear positive relationship between GrLivArea (above ground living area) and SalePrice, meaning larger homes generally sell for higher prices. This demonstrates that GrLivArea is a significant factor influencing house sale prices.
![image](https://github.com/user-attachments/assets/f2480272-58a9-4e35-891e-c6301f1ef8b5)

This graph tells the Numerical feature distribution.
![image](https://github.com/user-attachments/assets/5d7625c6-88b6-491a-8e4b-e3849cc68a43)


Then I trained the dataset on different models and the output was as follows-

1. Linear Regression-
   
Mean Squared Error: 1611519899.4528046

Root Mean Squared Error: 40143.74047660238

3. Lasso Regression:
   
  RMSE: 40133.21828114205

  R^2: 0.780603549042814

3.Ridge Regression:

  RMSE: 40130.12191260899
  
  R^2: 0.7806374016013723

4. Random Forest Regression:
   
  RMSE: 30424.301391002657
  
  R^2: 0.8739151654413598

6. XGBoost Regression:
   
  RMSE: 29865.323748311373
  
  R^2: 0.8785056512067712

8. LightGBM Regression:
   
  RMSE: 31944.09314635307
  
  R^2: 0.8610038565141291

From here i saw that the model performed best on XG Boost and Random Forest, so i applied it to Test.csv and these were the results-

1.Random Forest:

  RMSE: 28937.05
  
  R^2:  0.8908

  
2.XGBoost:

  RMSE: 28547.93
  
  R^2:  0.8937




