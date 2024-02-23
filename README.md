# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import the standard Libraries.

2.Set variables for assigning dataset values.

3.Import linear regression from sklearn.

4.Assign the points for representing in the graph.

5.Predict the regression for the marks by using the representation of the graph.

6.Compare the graphs and hence we obtained the linear regression for the given datas

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: Kamesh D
RegisterNumber: 212222240043
*/
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
plt.scatter(df['X'],df['Y'])
plt.xlabel('X')
plt.ylabel('Y')
X=df.iloc[:,0:1]
Y=df.iloc[:,-1]
X
from sklearn.model_selection import train_test_split
X_train,X_test,Y_train,Y_test=train_test_split(X,Y,test_size=0.2,random_state=0)
from sklearn.linear_model import LinearRegression
lr=LinearRegression()
lr.fit(X_train,Y_train)
X_train
Y_train
lr.predict(X_test.iloc[0].values.reshape(1,1))
plt.scatter(df['X'],df['Y'])
plt.xlabel('X')
plt.ylabel('Y')
plt.plot(X_train,lr.predict(X_train),color='red')
m=lr.coef_
m[0]
b=lr.intercept_
b
```

## Output:

![image](https://github.com/KameshLeVI/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120780633/97b55e2f-f2ed-4e54-a17f-51dc49f1e372)

![image](https://github.com/KameshLeVI/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120780633/cc3e25d5-c368-459b-989b-a6172f56c00e)

![image](https://github.com/KameshLeVI/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120780633/d671acc0-f20b-4763-aae0-e4485f4c48b2)

![image](https://github.com/KameshLeVI/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120780633/dc380c62-48f8-41ad-8533-d6aba101e88a)

![image](https://github.com/KameshLeVI/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120780633/5df9b90a-c081-4145-9dcf-3d2c0698ab55)

![image](https://github.com/KameshLeVI/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120780633/7cd9bbb7-94a7-47b2-af48-01d4ef6cd0b1)

![image](https://github.com/KameshLeVI/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120780633/353580d9-9f69-4406-a9ab-99ed5cb1c457)

## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
