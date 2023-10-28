# BharatIntern Task-2 : Titanic Classification

I am thrilled to share that I have successfully completed a comprehensive data science task as part of the BharatIntern program. The task involved developing a sophisticated system to predict the likelihood of survival during the Titanic sinking disaster, focusing on crucial factors such as socio-economic status, age, and gender, among others.

Description:

The Titanic Survival Prediction System is built using a dataset containing information about the passengers aboard the Titanic, such as their socio-economic status, age, gender, and other relevant features. By employing various machine learning algorithms, the system can determine the likelihood of a person surviving the disaster based on the provided input data.

Features:

Socio-Economic Status: Analyzing the impact of passenger class on survival rates.
Age: Studying the relationship between age and the likelihood of survival.
Gender: Investigating the influence of gender on survival probabilities.
Machine Learning Models: Utilizing classification algorithms for prediction, such as logistic regression, decision trees, random forests, or support vector machines.

Here's a basic outline of how you can approach this task:

1. Data Preprocessing:
    - Load the dataset into a pandas DataFrame.
    - Handle missing values, if any, by either imputing or removing them.
    - Encode categorical variables like 'sex' and 'embarked' into numerical values.
    - Split the data into training and testing sets.

2. Feature Engineering:
    - Create new features if required. For example, you can create a new feature 'family_size' by combining 'sibsp' and 'parch'.
    - Extract relevant information from existing features. For instance, extract titles from the 'Name' column.

3. Model Selection and Training:
    - Choose a suitable classification algorithm, such as logistic regression, decision trees, random forests, or support vector machines.
    - Train the model on the training data.

4. Model Evaluation:
    - Evaluate the model's performance on the test set using appropriate metrics such as accuracy, precision, recall, and F1-score.
    - Use techniques like cross-validation to ensure the model's robustness.

5. Feature Importance Analysis:
    - Analyze the importance of different features in predicting survival using the trained model.
    - Plot graphs or use statistical techniques to determine the most influential factors.

6. System Deployment:
    - Deploy the model using suitable frameworks like Flask or FastAPI.
    - Design a user-friendly interface for the system to input passenger information.
    - Display the prediction along with the factors contributing to the prediction.

7. Documentation and Reporting:
    - Document the entire process, including data preprocessing, model selection, and evaluation.
    - Explain the findings related to feature importance and factors influencing survival.
    - Write a comprehensive report summarizing the methodology and results for your LinkedIn profile.

Results

The system's predictions provide insights into the factors that were most likely to lead to survival during the Titanic disaster. Through the analysis of the model's output, it is possible to discern the significance of socio-economic status, age, gender, and other relevant variables in determining the survival outcomes.
