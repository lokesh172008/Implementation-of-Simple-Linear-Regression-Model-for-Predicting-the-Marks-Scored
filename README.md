# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: K.Lokesh Achari
RegisterNumber: 25012708

import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
X = np.array([1, 2, 3, 4, 5, 6, 7]).reshape(-1, 1)
Y = np.array([35, 40, 50, 60, 65, 70, 78])
model = LinearRegression()
model.fit(X, Y)
hours = float(input("Enter number of hours studied: "))
predicted_marks = model.predict([[hours]])
print("Predicted Marks Scored:", round(predicted_marks[0], 2))
plt.scatter(X, Y)
plt.plot(X, model.predict(X))
plt.xlabel("Hours Studied")
plt.ylabel("Marks Scored")
plt.title("Simple Linear Regression – Marks Prediction")
plt.show()

```

## Output:
<img width="1919" height="1079" alt="Screenshot 2026-01-24 093823" src="https://github.com/user-attachments/assets/b295a776-5266-463a-a90a-4ee2ff15a0a2" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
