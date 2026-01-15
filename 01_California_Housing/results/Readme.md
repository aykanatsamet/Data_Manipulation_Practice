CALIFORNIA HOUSING PROJECT - MODEL RESULTS

1. Model Performances:
----------------------
- Linear Regression:
  * Mean Squared Error (MSE): 0.53
  * R2 Score: 0.60

- Random Forest Regressor:
  * Mean Squared Error (MSE): 0.25
  * R2 Score: 0.81 (Best Model)

2. Key Findings:
----------------
- The Random Forest model performed significantly better than Linear Regression, explaining about 81% of the variance in house prices.
- Median Income (MedInc) was found to be the most influential factor on house prices.
- The dataset contained some outliers in 'AveRooms' and 'AveOccup' which were visualized in the boxplots.

3. Visuals in this folder:
--------------------------
- corr_image.png: Shows how features relate to the price.
- rf_model_image.png: Shows the accuracy of our best model.
