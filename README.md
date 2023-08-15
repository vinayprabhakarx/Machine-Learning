## *First library Install for ML*
- pip install numpy
- pip install pandas
- pip install matplotlib
- pip install -U sckit-learn
  - _for dicrect install in jupyter notebook start from !_
  - for eg. **!pip install pandas**
## For import library
-import numpy as np
-import pandas as pd
-import matplotlib.pyplot as plt
-import sklearn as scikit_learn

# mean_squared_error
- **from sklearn import datasets, linear_model**  is use to imort linear_model
-  **from sklearn.metrics import mean_squared_error** is use to calculate mean squared error
  - **MSE = (Σ(Y_pred - Y_true)^2) / n**
  - Mean Squared Error (MSE) is a widely used metric in statistics and machine learning to measure the average squared difference between the predicted values and the actual (true) values. It's particularly common in regression tasks, where you are trying to predict a continuous outcome based on input features.

#### **for eg.->**
-  **suppose,** Actual House Prices: [200, 300, 400, 600, 800], Predicted House Prices: [180, 320, 360, 550, 750]
  - Squared Difference for Data Point 1: (200 - 180)^2 = 400
  - Squared Difference for Data Point 2: (300 - 320)^2 = 400
  - Squared Difference for Data Point 3: (400 - 360)^2 = 1600
  - Squared Difference for Data Point 4: (600 - 550)^2 = 2500
  - Squared Difference for Data Point 5: (800 - 750)^2 = 2500
  - Sum up the squared differences: 400 + 400 + 1600 + 2500 + 2500 = 7400

  - Divide the sum by the number of data points (5 in this case): 7400 / 5 = 1480
