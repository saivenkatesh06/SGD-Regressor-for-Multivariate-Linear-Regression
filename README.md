# SGD-Regressor-for-Multivariate-Linear-Regression

## AIM:
To write a program to predict the price of the house and number of occupants in the house with SGD regressor.

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
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import SGDRegressor

# Dataset
X = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]).reshape(-1, 1)
y = np.array([10, 20, 30, 40, 50, 60, 70, 80, 90, 100])

# Create SGD Regressor model
model = SGDRegressor(max_iter=10000, learning_rate='constant',
                     eta0=0.001, random_state=42)

# Train the model
model.fit(X, y)

# Predict house price for 6 occupants
occupants = np.array([[6]])
predicted_price = model.predict(occupants)

print("Number of Occupants:", occupants[0][0])
print("Predicted House Price:", predicted_price[0])

# Plot graph
plt.scatter(X, y, color='blue', label='Actual Price')
plt.plot(X, model.predict(X), color='red', label='Prediction')
plt.xlabel("Number of Occupants")
plt.ylabel("House Price")
plt.title("House Price Prediction using SGD Regressor")
plt.legend()
plt.show()
*/
```

## Output:
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/271217a3-babc-4fca-bb6b-09d80f3d204a" />



## Result:
Thus the program to implement the multivariate linear regression model for predicting the price of the house and number of occupants in the house with SGD regressor is written and verified using python programming.
