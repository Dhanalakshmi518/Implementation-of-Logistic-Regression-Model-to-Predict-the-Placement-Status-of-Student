# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import all necessary packages and dataset that you need to implement Logistic Regression
2. Copy the actual dataset and remove fields which are unnecessary
3.Then select dependent variable and independent variable from the dataset.
4. And perform Logistic Regression.
5. print the values of confusion matrix, accuracy, Classification report to find whether the student is placed or
not

## Program:
```
/*
Program to implement the the Logistic Regression Model to Predict the Placement Status of Student.
Developed by: M.P.Dhanalakshmi
RegisterNumber:212225040063
import pandas as pd
import numpy as np
dfspd.read_(sv('/content/Placement_Data.csv')
df1=df.copy()
df1
df1=df1.drop(['s1_no', 'salary'], axis=1)
df1.isnul1().sum()
df1.duplicated().sum()
df1
from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
df1['gender']=le.fit_transform(dfI['gender'])df1['ssc_b']=le.fit_transform(df1['ssc_b'])df1['hsc_b'J=le.fit_transform(dfI['hsc_b"1)df1['hsc_s'1=le.fit_transform(df1['hsc s'1)
dfI['degree_t']=le.fit_transform(df1['degree_t'1)
df1['workex']=le.fit_transform(df1['workex']1)
df1['specialisation'J=le. fit_transform(dfI['specialisation'I)
dfI['status']=le.fit_transform(df1['status'1)
df1
x=df1.iloc[:, :-1]
y=df1['status'1
from sklearn.model selection import train test split
xtrain, x_test, y_train, y_test=train_test_split(x, y, test_size=0.2, random_state=0)
from sklearn.linear_model import LogisticRegression
model=LogisticRegression(solver="liblinear")
213
model.fit(x_train, y_train)
y pred=model.predict(x test)
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
accuracy=accuracy_score(y_test, ysred)confusion=confusion_matrix(y_test, y_pred)cr=classification_report(y_test, y_pred)print("Accuracy Score:", accuracy)
print("\nConfusion Matrix:1n", confusion)print("Inclassification Report:1n", cr)from sklearn import metrics
cndisplaymetrics.confusionatrixoisplay(confusion_matrixrconfusion, display_labels-('true', 'false
cn_display.plot()  
*/
```

## Output:
<img width="832" height="580" alt="WhatsApp Image 2026-05-11 at 4 07 27 PM" src="https://github.com/user-attachments/assets/9f20a154-c50f-4c7e-a38c-7cc87a82b75e" />
<img width="588" height="344" alt="WhatsApp Image 2026-05-11 at 4 07 38 PM" src="https://github.com/user-attachments/assets/17d58e6b-a689-4d36-9f96-296e61dcddf0" />




## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.
