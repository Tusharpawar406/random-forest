# Titanic Survival Prediction: Logistic Regression vs Random Forest

This project compares **Logistic Regression** and **Random Forest** models to predict Titanic passenger survival.


## Dataset
Dataset: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)  
File used: `train.csv`


## Objective
Build two classification models and compare their performance on predicting passenger survival.



## Steps Involved
1. **Data Preprocessing**
   - Filled missing values (`Age`, `Fare`, `Embarked`)
   - Encoded categorical features (`Sex`, `Embarked`)
2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions and correlations
3. **Model Training**
   - Trained Logistic Regression (`max_iter=500`)
   - Trained Random Forest (`n_estimators=500`)
4. **Evaluation**
   - Compared accuracy, precision, recall, and F1-score
   - Visualized Random Forest feature importance



## Results
- Logistic Regression Accuracy: ~80–82%  
- Random Forest Accuracy: ~85–88%  
- Top features influencing survival: `Sex`, `Pclass`, `Fare`, `Age`



## Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  



## Conclusion
Random Forest outperformed Logistic Regression on the Titanic dataset, capturing nonlinear patterns and interactions between features. Both models indicate that **gender, class, and fare** were the most important factors affecting survival.
