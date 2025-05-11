# 🛢️ OilyGiant Mining Company - Oil Well Location Selection

## 📌 Project Overview
The OilyGiant Mining Company is on a task to find the best location for a new oil well. Using data from three regions including key geological features and reserve volumes, a model was built to predict oil reserves and identify the most profitable and least risky region for development. 

## 🎯 Key Goals:
1. Collect oil well data from tree regions
2. Train a machine learning model to predict reserves
3. Analyze profits and risks to choose the optimal region

## 📚 Table of Contents
- Project Overview
- Key Goals
- Data Description
- Data Preparation
- Model Training & Testing
- Profit Calculation
- Bootstrapping & Risk Analysis
- Conclusion
- Credits

## 🧾 Data Description
I worked with synthetic data from three regions:
- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`

Each dataset includes:
- `id`: Unique well identifier
- `f0`, `f1`, `f2`: Geological features
- `product`: Reserve volume (in thousand barrels)

## 🧹 Data Preparation
I split the data into:
- 75% for training
- 25% for validation

## 🧠 Model Training & Testing
A Linear Regression model was trained for each region to predict oil reserves. The performance was measured using RMSE (Root Mean Squared Error)

## 💵 Profit Calculation
Profitability was estimated as 4500 USD Revenue per barrel based on the budget of 100 million USD and a drilling plan for 200 wells. 
The aim was to ensure that the predicted reserves are sufficient to avoid losses and generate maximum returns. 

## 📈 Bootstrapping & Risk Analysis
I applied the Bootstrapping technique with 1000 samples to stimulate profit distribution and analyze uncertainty:
- Average Profit
- 95% Confidence nIterval
- Risk of Loss

### 🧾 Results:
- Region 1 had the lowest risk (1.6%) and the highest average profit
- Regions 0 and 2 had higher risk and potential for loss

## ✅ Conclusion
- Region 1 is the best choice for new well development. 
   -  High accuracy in predictions
   -  Low risk of loss (1.6%)
   -  Highest potential profit

## 🤝 Credits
This project was created as part of the TripleTen Data Science program. Special thanks to: 
   - TripleTen instructors and peers for ongoing support and feedback
