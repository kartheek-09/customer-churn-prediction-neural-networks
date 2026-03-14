

# Credit Card Customer Churn Prediction using Deep Learning

## Overview

This project focuses on predicting whether a **bank customer will leave the bank (customer churn)** using a **Deep Learning Artificial Neural Network (ANN)** model. Customer churn prediction is an important task for banks and financial institutions because retaining existing customers is significantly more cost-effective than acquiring new ones.

By analyzing various customer attributes such as credit score, age, balance, and activity status, the model learns patterns that indicate whether a customer is likely to exit the bank. This predictive approach helps organizations take proactive measures to improve customer retention.

---

# Dataset

The project uses a **Credit Card Customer dataset** containing information about bank customers and their banking behavior.

The dataset includes features such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products Used
* Credit Card Ownership
* Active Membership Status
* Estimated Salary

### Target Variable

The target variable indicates whether a customer has left the bank.

* **0 → Customer stays with the bank**
* **1 → Customer leaves the bank**

---

# Technologies Used

The project is implemented using the following technologies and tools:

* Python
* Pandas (Data Analysis)
* NumPy (Numerical Computation)
* Scikit-learn (Machine Learning Utilities)
* TensorFlow / Keras (Deep Learning Framework)
* Matplotlib (Data Visualization)

---

# Project Workflow

## Data Preprocessing

The dataset is first cleaned and prepared for model training. Unnecessary columns that do not contribute to prediction are removed. Categorical features such as gender and geography are converted into numerical representations so that they can be used by machine learning models.

## Feature Engineering and Scaling

To ensure better model performance, the input features are standardized. Feature scaling helps neural networks train faster and improves convergence.

## Dataset Splitting

The dataset is divided into training and testing sets. The training set is used to train the neural network, while the testing set is used to evaluate the model's performance on unseen data.

## Model Development

A **Multilayer Perceptron (MLP)** neural network is designed using multiple layers of neurons. The network learns complex relationships between customer attributes and churn behavior.

## Model Training

The neural network is trained using historical customer data. During training, the model adjusts its internal weights to minimize prediction errors.

## Model Evaluation

After training, the model is evaluated using the testing dataset to measure how accurately it predicts customer churn.

---

# Model Architecture

The deep learning model consists of multiple layers:

* Input Layer – receives customer feature data
* Hidden Layers – extract complex patterns from the data
* Output Layer – predicts the probability of customer churn

A sigmoid activation function is used in the final layer to generate binary classification results.

---

# Results

The trained neural network successfully identifies patterns that indicate whether a customer is likely to leave the bank. The model demonstrates how deep learning techniques can be applied to real-world business problems in the banking and financial sectors.

---

# Applications

Customer churn prediction models can help organizations:

* Identify customers who are likely to leave
* Develop targeted retention strategies
* Improve customer satisfaction and loyalty
* Reduce financial losses due to churn

---

# Future Improvements

Several improvements can enhance the model further:

* Hyperparameter tuning for better performance
* Adding dropout layers to prevent overfitting
* Using advanced ensemble models for comparison
* Training on larger and more diverse datasets

---

# Conclusion

This project demonstrates the application of **Deep Learning techniques for customer churn prediction in the banking sector**. By leveraging customer behavioral data and neural networks, organizations can make informed decisions and implement proactive strategies to retain valuable customers.

---


