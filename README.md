Student Performance Prediction using Machine Learning

Introduction:

Hello everyone, I'm Chetna, a data scientist.This repository contains my project on predicting student performance using machine learning.

Dataset:

- Source: Kaggle
- Number of students: 2392
- Features: demographic details, study habits, parental involvement, extracurricular activities, and academic performance
- Target variable: Grade classification

  
Methodology:

1. Importing Libraries and Loading Data
2. Exploratory Data Analysis (EDA)
    - Checking for NaN values and outliers
    - Understanding data distribution
3. Target Variable Extraction
4. Data Splitting
    - Training set
    - Testing set
5. Machine Learning Algorithms
    - K-Nearest Neighbors (KNN)
    - Logistic Regression
    - Decision Tree
    - Random Forest
6. Hyperparameter Tuning
    - Improving accuracy using Decision Tree

Results:

- Accuracy comparison of machine learning algorithms
- Decision Tree yields best results
- Hyperparameter tuning improves accuracy to 91%

Libraries Used

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Conclusion:

Dataset: Student performance data
Preprocessing: EDA, data splitting (training and testing)
Algorithms: Compared 4 algorithms, with Decision Tree performing best
Hyperparameter Tuning: Improved Decision Tree performance
Evaluation Metrics:
        Precision: 85%
        Recall: 73%
        F1 Score: 79%
        Accuracy: 91%

        
Recommendations:

Model Deployment: Integrate the trained Decision Tree model into the educational institution's system to predict student performance.
Feature Engineering: Explore additional relevant features to further improve model accuracy.
Model Interpretability: Analyze feature importance to identify key factors influencing student performance.
Continuous Monitoring: Regularly update the model with new data to maintain accuracy.
Comparison with Other Models: Compare Decision Tree with other ensemble methods (e.g., Random Forest) to potentially improve performance.



