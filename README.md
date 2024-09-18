### Predicting Aircraft Remaining Useful Life (RUL) Using Machine Learning

To develop a machine learning framework capable of accurately predicting the remaining useful life of aircraft components based on their historical performance data. This will enable proactive maintenance strategies to ensure optimal aircraft reliability and performance.

#### Methodology:
##### Data Acquisition: 
Utilize the NASA C-MAPSS dataset, which contains comprehensive information on aircraft engine performance throughout their lifecycles.
##### original resource : 
https://data.nasa.gov/Aerospace/CMAPSS-Jet-Engine-Simulated-Data/ff5v-kuh6/about_data
##### Data Set: FD001 will use as training dataset
Train trjectories: 100
Test trajectories: 100
Conditions: ONE (Sea Level)
Fault Modes: ONE (HPC Degradation)

##### Feature Engineering:
Extract relevant features from the raw data, such as sensor readings, operating conditions, and maintenance history.
##### Model Selection and Training:
Experiment with various regression and classification models (e.g., Linear Regression, Decision Tree, Random Forest, SVM , XGBoost) to identify the most effective approach for predicting RUL.

##### Model Evaluation: 
Assess the performance of each model using appropriate metrics (e.g., accuracy, Mean Absolute Error) to select the best-performing model.