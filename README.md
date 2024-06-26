 #Sharing this Python code for detecting dyslexia using eye tracking data. This code is a machine learning approach to classify dyslexia based on eye movement patterns.The key aspects of the code are summerized below:

Data Preparation:
The code reads data from a CSV file named "nikhila.csv".
It calculates new features 'll' and 'rr' based on eye position coordinates.
Some columns are dropped, including individual coordinate columns and the 'name' column.

Data Cleaning:
Outliers are detected and removed using the IQR method for both 'll' and 'rr' features.

Data Preprocessing:
The 'gender' and 'dyslexia' columns are label-encoded.
The features are standardized using StandardScaler.

Model Training:
A Random Forest Regressor is used as the classification model.
The data is split into training (80%) and testing (20%) sets.

Model Evaluation:
Accuracy, confusion matrix, precision, recall, and F1 score are calculated.
