# Language Detection Model
# Overview
* This project demonstrates a Language Detection Model built using Python in Google Colab. The model is designed to automatically identify the language of a given text input using machine learning techniques.
* For feature extraction, the project uses TF-IDF vectorization with character-level n-grams, which helps the model effectively capture language-specific patterns. A machine learning pipeline is implemented to streamline the process of vectorization and classification.
* Multiple models were trained and evaluated, including Logistic Regression, Naive Bayes, and Support Vector Machines (SVM). Hyperparameter tuning was performed using GridSearchCV to optimize model performance.
* Among all models, the Linear SVM achieved the best results with an accuracy of approximately 99.17% on the test dataset.
The project also includes performance evaluation using classification reports and confusion matrices, as well as a prediction function that allows users to input custom text and detect its language in real time.

# Dataset
The dataset used is sourced from: https://www.kaggle.com/datasets/abhishekkaggle8585/language-detection-dataset
* The dataset consists of over 10,000 text samples across multiple languages including English, French, Spanish, Arabic, Hindi, and more. The data is first preprocessed through cleaning steps such as lowercasing, removing punctuation, numbers, and extra spaces to ensure consistency and improve model performance.
