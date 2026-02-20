# HR Analytics: Employee Attrition Prediction

![HR Analytics](https://img.shields.io/badge/Pet_Project-HR%20Analytics-blue)
![Problem](https://img.shields.io/badge/Problem-Employee%20Attrition-green)
![ML](https://img.shields.io/badge/Type_of_ML-Binary%20Classification-yellow)
![Environment](https://img.shields.io/badge/Environment-Google%20Colab-orange)

---

## Project Overview
Personal project analyzing **employee attrition** to identify high-risk employees and provide actionable HR insights.  
Demonstrates **EDA, feature engineering, modeling** and **business-oriented insights**.

**Objectives:**
- Understand attrition patterns and risk factors.
- Build predictive models for attrition.
- Suggest data-driven retention strategies.

---

## Data
- **Dataset:** **«HR Analytics. Employee Attrition Dataset»** (Kaggle [link](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction))  
- 1470 employees, 34 features (demographic, education background, job, financial and career)  
- Target: `Attrition` (Yes/No)

---

## Methods & Tools
- **EDA & Visualization:** Pandas, Seaborn, Matplotlib, Plotly  
- **Feature Engineering:** Binary & one-hot encoding, scaling, feature selection  
- **Models:** Logistic Regression, Gaussian NB, Balanced Random Forest, XGBoost, LightGBM, MLP, Bagging  
- **Imbalance Handling:** SMOTE, class weights  
- **Metrics:** ROC-AUC, Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## Key Insights
- **Attrition risk**: Highest in the first **2 years**: onboarding and early-career support are key intervention points. Attrition declines steadily with tenure and is concentrated among junior employees.
- **Structural drivers**: Attrition is not random; it is linked to organizational and work-related factors. Overtime is associated with higher attrition and does not correspond to proportional income growth.
- **Age & hierarchy**: Higher JobLevel and education correspond to older employees. Managerial and director roles are held by senior staff, while operational roles are younger-skewed.
- **Income structure**: Income rises consistently with experience, tenure and JobLevel. Managers and Research Directors earn the most; operational roles earn the least.

---

## Modeling Highlights
- **Best model:** Logistic Regression
- **SMOTE:** Conservative, high precision  
- **Class weights:** Captures more leavers, higher recall  
- **Business tip:** Choose SMOTE for precision-focused monitoring; class weights for recall-focused intervention.
