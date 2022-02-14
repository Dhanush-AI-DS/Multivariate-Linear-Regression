# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
Developed by : Dhanush.s
Ref No: 212221230020

import pandas as pd
from sklearn import linear_model 
df=pd.read_csv("cars.csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('coefficients:',regr.coef_)
print('Intercept:', regr.intercept_)
predictedco2 = regr.predict([[3300, 1300]])
print('predicted CO2 for the corresponding weight and volume',predictedco2)

```
## Output:
![gitlogo](carsS.png)



<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
