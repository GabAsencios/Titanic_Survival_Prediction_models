# Titanic_Survival_Prediction_models
Running the Code

Option 1: Jupyter Notebook

Open Logistic_Regression&Perceptron_Models.ipynb

Ensure Titanic.csv is in the correct path

Run all cells sequentially


Option 2: Google Colab

Upload Logistic_Regression&Perceptron_Models.ipynb to Google Colab

Upload Titanic.csv using the file upload button

Verify the path is /content/Titanic.csv

Run all cells


Project Structure:

1. Data Preprocessing

Handle missing values (Age, Embarked, Fare)
Feature engineering (FamilySize, IsAlone)
One-hot encoding for categorical variables


2. Logistic Regression Model

Hyperparameter exploration (C, solver, penalty)
GridSearchCV for optimal parameters
Achieved ~79% accuracy


3. Perceptron Model

Feature scaling with StandardScaler
Hyperparameter tuning (alpha, eta0)
Achieved ~75% accuracy


4. Model Evaluation

Classification report
Confusion matrix analysis
Feature importance ranking
Performance comparison
