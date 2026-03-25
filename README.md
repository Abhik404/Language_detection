# Language Detection Model

# Dataset
The dataset used is sourced from: https://www.kaggle.com/datasets/abhishekkaggle8585/language-detection-dataset
* The dataset consists of over 10,000 text samples across multiple languages including English, French, Spanish, Arabic, Hindi, and more. The data is first preprocessed through cleaning steps such as lowercasing, removing punctuation, numbers, and extra spaces to ensure consistency and improve model performance.

# Overview
This project demonstrates a Language Detection Model built using Python in Google Colab. The model is designed to automatically identify the language of a given text input using machine learning techniques.
# Features
* Data cleaning and preprocessing pipeline
* TF-IDF vectorization (character n-grams)
* Multiple model comparison
* Hyperparameter tuning with GridSearchCV
* High accuracy (~99.17%)
* Real-time language prediction function
# Model Details
* Models Used: Logistic Regression, Naive Bayes, Linear SVM
* Best Model: Linear Support Vector Machine (SVM)
* Vectorization: TF-IDF (character-level n-grams)
* Dataset Size: 10,000+ text samples
* Languages Covered: 15+ languages including English, French, Spanish, Arabic, Hindi, etc.
# Results
* Achieved ~99.17% accuracy on the test dataset
* Strong performance across multiple languages
* Effective handling of multilingual text inputs
# Demo
Input any text, and the model will automatically detect and return the predicted language in real time.
