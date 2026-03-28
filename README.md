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
import pandas as pd
from sklearn import linear_model
df = pd.read_csv("carsemission.csv")
X = df[['Weight', 'Volume']]
y = df['CO2']
regr = linear_model.LinearRegression()
regr.fit(X, y)
print('Coefficients:', regr.coef_)
print('Intercept:', regr.intercept_)
input_data = pd.DataFrame({'Weight': [3300], 'Volume': [1300]})
predictedCO2 = regr.predict(input_data)
print('Predicted CO2 for the corresponding weight and volume:', predictedCO2)









## Output:

<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/790533e3-ba8b-4758-a0db-a102b4cb8566" />

<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/89811f5b-8a52-44e0-8690-aca0d71d6ff1" />


<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/88c9e1c1-16bb-46e3-a850-8ad0cf2c0472" />




## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
