# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
### Algorithm:
### Step1
<br>Import Libraries: Import Pandas and Linear Regression from Scikit-learn.

### Step2
<br>Load Dataset: Read the carsemission.csv dataset using Pandas.
### Step3
<br>Select Variables: Choose Weight and Volume as input features (X) and CO2 as the target variable (Y).

### Step4
<br>Train the Model: Create a Linear Regression model and train it using regr.fit(X, y). Display the coefficients and intercept.

### Step5
<br>Predict CO₂ Emission: Give Weight = 3300 and Volume = 1300 as input, predict the CO₂ emission, and display the result.


### Program:

Developed by: Sanjay R
Register no: 26009894
### import pandas as pd

### url = "https://raw.githubusercontent.com/arunpradeep-sec/Linear-Algebra-Lab/main/carsemission.csv"

### df = pd.read_csv(url)
### df.to_csv("carsemission.csv", index=False)

### print("Dataset loaded successfully.")

### import pandas as pd
### from sklearn import linear_model
### df = pd.read_csv("carsemission.csv")
### X = df[['Weight', 'Volume']]
### y = df['CO2']
### regr = linear_model.LinearRegression()
### regr.fit(X, y)
### print('Coefficients:', regr.coef_)
### print('Intercept:', regr.intercept_)
### input_data = pd.DataFrame({'Weight': [4000], 'Volume': [4000]})
### predictedCO2 = regr.predict(input_data)
### print('Predicted CO2 for the corresponding weight and volume:', predictedCO2)






``
## Output:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c3e4b6c3-15c0-4315-a95b-aa3fe4a34877" />


<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
