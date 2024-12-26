# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Import pandas

### Step 2: Import linear model from sklearn

### Step 3: Read the file cars.csv

### Step 4: Assign the values for x and y as required

### Step 5: Create the linearRegression model and predict the output


## Program:
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("/content/car.csv")
x=df[['Volume','Weight']]
y=df['CO2']
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))


```
## Output:

### Insert your output
![alt text](<Screenshot 2024-12-26 222328.png>)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.