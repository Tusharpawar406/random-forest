# Titanic Survival Prediction using Random Forest

This project predicts whether a passenger survived the Titanic disaster using a **Random Forest Classifier**.

---

## Dataset
Dataset: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)  
File used: `train.csv`

---

## Objective
Build a classification model to predict passenger survival and identify the most important features influencing survival.

---

## Steps Involved
1. **Data Preprocessing**
   - Filled missing values (`Age`, `Fare`, `Embarked`)
   - Encoded categorical features (`Sex`, `Embarked`)
2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions and correlations
3. **Model Training**
   - Trained a Random Forest Classifier (`n_estimators=500`)
4. **Evaluation**
   - Measured accuracy, confusion matrix, precision, recall, and F1-score
   - Plotted feature importance

---

## Results
- Accuracy: ~85–88%  
- Most important features for survival:
  - `Sex` (female passengers more likely to survive)
  - `Pclass` (higher class increased survival chance)
  - `Fare` (higher fare associated with higher survival)
  - `Age` (younger passengers more likely to survive)

---

## Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## Conclusion
Random Forest effectively predicts passenger survival and captures nonlinear relationships between features. Feature importance highlights key factors influencing survival, making the model both accurate and interpretable.

