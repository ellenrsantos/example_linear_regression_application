# 📊 Different Types of Linear Regression Applied in Dataset of various cars from Car Dekho (Kaggle Dataset).

![image](https://github.com/user-attachments/assets/dd9197eb-27d5-4c8c-b83c-e9b2fc78835a)

# 📜 Context:

In this work I explored differents types of Python Libraries for Linear Regression (Scikit Learn).

# 📖 Description:

For this analysis, I chose a open acess dataset available in Kaggle (link below) about various cars from Car Dekho.

Acess link: [https://www.kaggle.com/datasets/mirichoi0218/insurance/code?datasetId=13720&sortBy=voteCount](https://www.kaggle.com/datasets/akshaydattatraykhare/car-details-dataset/data)

📓 If you want to see more graphics and the exploratory analysis, jupyter notebook is available. 

# 💡 Insights:

1 - LGBMRegressor is the best model with the highest R² score (75.68%) and solid generalization ability.

2 - Random Forest and Gradient Boosting are close competitors but still slightly underperform LGBM.

3 - XGBoost shows strong performance but overfits more, achieving a lower R² (73.0%).

4 - Bagging and Decision Tree models also overfit and have lower test scores.

5 - Linear Regression is the weakest performer, with an R² of 47.24%, indicating it struggles with the dataset's complexity.


📊 Model Comparison Summary - Top 3 Performing Models (Based on R² Score):

🥇 LGBMRegressor: (https://lightgbm.readthedocs.io/en/latest/pythonapi/lightgbm.LGBMRegressor.html)
- Cross-Validation: 62.43%
- Training Score: 78.16%
- Testing Score: 75.68%
- R² Score: 75.68% → Best performer
  
🥈 RandomForestRegressor: (https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
- Cross-Validation: 62.34%
- Training Score: 88.78%
- Testing Score: 74.24%
- R² Score: 74.24%
  
🥉 GradientBoostingRegressor: (https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)
- Cross-Validation: 61.01%
- Training Score: 73.93%
- Testing Score: 74.15%
- Score: 74.15%

  ![image](https://github.com/user-attachments/assets/c7875514-fa10-4eda-b6ce-f10a4deb63d5)


# 📌 References:
1) https://www.kaggle.com/datasets/akshaydattatraykhare/car-details-dataset/data
