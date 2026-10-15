TITANIC PASSENGER SURVIVAL PREDICTION USING MACHINE LEARNING
Project Description
Titanic Passenger Survival Prediction is a machine learning project developed to predict whether a passenger survived the Titanic disaster using historical passenger data. The project focuses on understanding passenger information, preparing the dataset, and applying a classification algorithm to predict survival outcomes.
The project was developed and executed in VS Code using Python and Jupyter Notebook. It covers data preprocessing, missing-value handling, categorical encoding, feature preparation, model training, and prediction. The objective is to understand how machine learning techniques can identify patterns in passenger data and use them to make predictions.
Project Objectives
- Analyze the Titanic dataset and understand passenger survival patterns.
- Handle missing values and prepare the data for model training.
- Convert categorical variables into numerical representations.
- Separate input features and the target variable.
- Train a machine learning classification model to predict passenger survival.
- Evaluate model performance using appropriate metrics.
Dataset Details
The project uses the titanic_data.csv dataset containing passenger-related information. Features include passenger class, sex, age, family relationships aboard the ship, ticket fare, and embarkation port, depending on the available dataset columns.
The target variable is Survived, where 1 indicates survival and 0 indicates non-survival.
Data Preprocessing
The dataset is loaded and examined to understand its structure and identify missing values. Data preprocessing is performed to prepare the dataset for machine learning.
Categorical variables are converted into numerical values. The sex column is transformed using Pandas get_dummies(), while the embarked column is encoded using Scikit-learn's LabelEncoder. The input features and target variable are then separated for model development.
Model Development
The project uses a Random Forest classifier to predict passenger survival. A Decision Tree model was considered during the initial development, and the notebook was later updated to use Random Forest.
Random Forest combines predictions from multiple decision trees to produce a final classification. The trained model learns patterns from the prepared dataset and uses them to predict survival outcomes.
Model Evaluation
The model is evaluated using the evaluation steps implemented in the notebook. Its predictions and performance are examined to understand how effectively it classifies passenger survival outcomes.
Technologies Used
Python for programming and model development.
Pandas and NumPy for data manipulation and preprocessing.
Scikit-learn for categorical encoding, classification, and model evaluation.
Jupyter Notebook for writing and executing the machine learning workflow.
VS Code for project development and execution.
Project Structure
The project contains titanic_data.csv, which stores the dataset, and train.ipynb, which contains the Python code for data preprocessing, feature preparation, model training, and prediction.
Project Workflow
The workflow begins by loading and examining the dataset. Missing values are handled, categorical columns are encoded, and input features and the target variable are prepared. The Random Forest classifier is then trained and used to generate predictions. Model performance is evaluated based on the implemented workflow.
Conclusion
This project demonstrates the application of machine learning classification techniques to passenger survival prediction. It provides practical experience in data preprocessing, categorical encoding, feature preparation, Random Forest classification, and model evaluation. Developing and executing the workflow in VS Code also provides hands-on experience in building a machine learning project using Python and Scikit-learn.
