# Bank_Churn_Prediction
This project is a Streamlit-based web application that predicts whether a bank customer will leave the bank (churn) based on several features such as tenure, balance, number of products, and more. It uses a machine learning model trained to classify customers as either staying or leaving based on historical data.



## Key Features:

* User Input Form: The app provides an intuitive form for users to input customer information (e.g., tenure, balance, number of products).
* Imbalanced Dataset Handling: The dataset used for this project had imbalanced classes, where a majority of customers stayed with the bank, and only a minority left. This imbalance was addressed using the oversampling technique (such as SMOTE or RandomOverSampler), ensuring that the model is not biased towards the majority class.
* Real-time Prediction: The app provides instant predictions on whether a customer is likely to churn or stay based on the input features.
* Machine Learning Model: The app utilizes a pre-trained machine learning model that predicts customer churn using scikit-learn.
* Categorical Input Handling: Categorical features such as geography, gender, and card type are handled with one-hot encoding for accurate prediction.

## Technologies Used:

* Python: The primary programming language used to build the app and integrate the model.
* Streamlit: Framework for creating the user interface and interactive components.
* Scikit-learn: Used to build, train, and evaluate the machine learning model.
* Imbalanced-learn: Used to handle the imbalanced dataset and apply oversampling techniques (e.g., SMOTE).
* Joblib: For saving and loading the pre-trained machine learning model.
* NumPy & Pandas: For numerical computations and data processing.

  
## How It Works:

* Input Data: The user enters the customer's details such as tenure, balance, geography, and more.
* Model Prediction: The app predicts whether the customer will churn based on the input.
* Imbalance Handling: The model was trained on an imbalanced dataset, and oversampling techniques were applied to balance the dataset and improve the prediction accuracy.
* Result: The app displays a message predicting whether the customer will leave or stay.

  
