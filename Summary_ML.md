
# <div style="background-color: white; text-align: center"><img src="heart_image.png" alt="Heart" title="Heart Image" width="50" height="50" /><font color=red> <span style="font-size: 95%; background-color: white;">Summary of Heart Disease Classification Using Machine Learning</span> </font><img src="heart_image.png" alt="Heart" title="Heart Image" width="50" height="50" /></div>

## Dataset Features
1. Age: Age of the patient (Numerical Continuous)
2. Sex: Gender of the patient (Binary Categorical)
3. cp: Chest Pain type (Ordinal Categorical)
4. trestbps: Resting Blood Pressure (Numerical Continuous)
5. chol: Serum Cholestrol (Numerical Continuous)
6. fbs: Fasting Blood Sugar (Binary Categorical)
7. restecg: Resting Electrocardiographic Results (Ordinal Categorical)
8. thalach: Maximum Heart Rate Achieved (Numerical Continuous)
9. exang: Exercise Induced Angina (Binary Categorical)
10. oldpeak: ST Depression induced by exercise relative to rest (Numerical Continuous)
11. slope: Slope of the peak exercise ST segment (Ordinal Categorical)
12. ca: Number of major vessels (0-3) colored by Flourosopy (Ordinal Categorical)
13. thal: Thalassemia (Ordinal Categorical)
14. target: Heart Disease (Binary Categorical)

## Machine Learning

### Preprocessing the Data
- Data is split into feature matrix `X` and target vector `y`.
- The dataset is further split into training and testing sets.

### Data Encoding and Scaling
- Ordinal encoding is applied to ordinal categorical features.
- StandardScaler is used for feature scaling.

### Model Building and Evaluation

#### Logistic Regression
- Produced an accuracy score of <font color=red>86.88%</font>.
- Confusion Matrix


#### Support Vector Machine (SVM)
- Produced an accuracy score of <font color=red>86.89%</font>.
- Confusion Matrix

#### Decision Tree
- Produced an accuracy score of <font color=red>81.97%</font>.
- Confusion Matrix

#### Random Forest
- Produced an accuracy score of <font color=red>83.61%</font>.
- Confusion Matrix

#### K-Nearest Neighbors (KNN)
- Achieved an accuracy score of <font color=red>86.89%.</font>
- Confusion Matrix

#### Naive Bayes
- Produced an accuracy score of <font color=red>86.89%</font>.
- Confusion Matrix

In conclusion, various machine learning models were trained and evaluated on the heart disease dataset. Logistic Regression performed the best with an accuracy score of 86.88%, followed by SVM and KNN. These results provide valuable insights for predicting heart disease occurrences.
