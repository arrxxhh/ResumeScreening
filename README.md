>>RESUME SCREENING SYSTEM
This project implements a machine learning-based classification system to categorize resumes into predefined categories. The system preprocesses the data, balances classes, and uses multiple classifiers (KNN, SVM, Random Forest, Logistic Regression) to predict resume categories.
Authors: Arshpreet Singh, Era Pathania

>>FEATURES
1. Data Preprocessing:
    Removal of URLs, hashtags, mentions, special characters, and punctuation.
    Cleaning resumes for better classification.
2. Class Balancing:
    Oversampling to handle class imbalances.
    SMOTE
4. Text Vectorization:
    TF-IDF vectorizer for converting text data into numerical features.
5. Classification Models:
    Multiple models implemented:
    K-Nearest Neighbors (KNN)
    Support Vector Machine (SVM)
    Random Forest
    Logistic Regression
6. Prediction System:
    Predicts the category of a new resume using trained models.

>>DEPENDECIES
1. numpy
2. pandas
3. matplotlib
4. scikit-learning
5. re
6. sklearn

##to install these dependecies
!pip install numpy pandas matplotlib scikit-learn re


>>DATASET
The dataset used for training is a CSV file named UpdatedResumeDataSet.csv by Github , containing resumes and their corresponding categories.


>>HOW TO RUN
1. Open the .ipnyb file
2. Download the Dataset
3. Replace the dataset location as per your device
4. Clear all existing outputs (optional)
5. Restart the Kernal before each use
6. Run All/Run cell-wise to view the output
