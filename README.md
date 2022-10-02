<div align="center">
  <h1>🛣️ Time series Prediction - Road Dataset</h1>
  
  Time series prediction for Road Dataset
</div>

## ❓ Problem
Given data of 13 sensors computed annually over 10 years for sections of road. Build a model that predicts the data for sensors 9-13, as these sensors would be removed and reused(as these are costly). 

## ✍️ Approach
1. Preprocessing and Data Cleaning
    1. Populate 'Section' column
    2. Find missing year data for sections, since only 1 row was missing, duplicated data for the required year for that section
    3. Populate ```Nan``` values
2. Compare models
3. Analyse and find model with best square deviation (ExtraTreesRegressor, in our case)
4. Calculate RMSE

## 🎉 Results
The total RMSE value of the model is 

## ✨ Contributing
Yes, please! Feel free to contribute, raise issues and recommend best practices.
