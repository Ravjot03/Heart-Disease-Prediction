# Heart Disease Prediction Project

## Heart Disease Prediction using Logistic Regression

## Problem:
World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression.

## Solution:
The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD). 

I have implemented Logistic Regression Model to predict Coronary Heart Disease.

**What is Logistic Regression ?**

*Logistic Regression is a statistical and machine-learning techniques classifying records of a dataset based on the values of the input fields . It predicts a dependent variable based on one or more set of independent variables to predict outcomes . It can be used both for binary classification and multi-class classification.*

---
## Data info:
The dataset is available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

The dataset is already provided in the repository ([here](https://github.com/Ravjot03/Heart-Disease-Prediction/blob/master/framingham.csv)).

Framingham Heart study dataset includes several demographic risk factors:-
1. `sex`: male or female
2. `age`: age of the patient
3. `education`: levels coded 1 for some high school, 2 for a high school diploma or GED, 3 for some college or vocational school, and 4 for a college degree.

The data set also includes behavioral risk factors associated with smoking

4. `currentSmoker`: whether or not the patient is a current smoker
5. `cigsPerDay`: the number of cigarettes that the person smoked on average in one day.

Medical history risk factors

6. `BPMeds`: whether or not the patient was on blood pressure medication
7. `prevalentStroke`: whether or not the patient had previously had a stroke
8. `prevalentHyp`: whether or not the patient was hypertensive
9. `diabetes`: whether or not the patient had diabetes

Risk factors from the first physical examination of the patient.

10. `totChol`: total cholesterol level
11. `sysBP`: systolic blood pressure
12. `diaBP`: diastolic blood pressure
13. `BMI`: Body Mass Index
14. `heartRate`: heart rate
15. `glucose`: glucose level
16. `TenYearCHD`: 10 year risk of coronary heart disease CHD *(TARGET VARIABLE)*

---
## Libraries Used - 
  1. Pandas *(for data manipulation)*
  2. Matplotlib *(for data visualization)*
  3. Seaborn *(for data visualization)*
  4. Scikit-Learn *(for data modeling)*

---
## Contents:
1. Importing the required libraries.
2. Importing and Reading the dataset.
3. Exploratory Data Analysis (EDA)
4. Data-Preprocessing
5. Data Visualization
    - Correlation Matrix
    - Pairplot
    - Countplots
6. Data Modeling
    - Separating the data into features and target variable.
    - Splitting the data into training and test sets.
    - Modeling/ Training the data
    - Predicting the data
    - Calculating the prediction scores
    - Getting the model's accuracy
        - Classification Report
        - Confusion Matrix
        - Plotting the confusion matrix
