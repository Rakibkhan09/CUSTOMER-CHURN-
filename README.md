# Customer Churn Prediction using Artificial Neural Network

## 📌 Project Overview

Customer churn refers to customers who stop using a company's services. Predicting churn helps businesses identify customers who are likely to leave and take preventive actions.

In this project, customer data is analyzed and an **Artificial Neural Network (ANN)** is developed to predict whether a customer is likely to churn.

The project covers:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- ANN Model Development
- Model Evaluation

---

## 🎯 Problem Statement

The objective of this project is to:

- Analyze customer behavior.
- Identify factors related to customer churn.
- Prepare the dataset for machine learning.
- Build an ANN classification model.
- Evaluate the model's performance.

---

## 📂 Dataset

The dataset contains customer information related to:

- Customer demographics
- Services
- Account information
- Contract details
- Monthly charges
- Total charges
- Customer churn

### Target Variable

**Churn**

- `Yes` → Customer churned
- `No` → Customer did not churn

The `customerID` column was removed because it does not provide useful predictive information.

---

## 🔍 Exploratory Data Analysis

The following EDA techniques were performed:

- Dataset shape and structure
- Data types
- Descriptive statistics
- Missing value analysis
- Duplicate analysis
- Numerical feature analysis
- Categorical feature analysis
- Distribution analysis
- Boxplots for outlier analysis
- Churn distribution
- Numerical features vs Churn
- Categorical features vs Churn
- Correlation analysis

---

## ⚙️ Feature Engineering

Feature engineering was performed to create meaningful information from the existing customer data.

Examples include:

- Customer tenure categories
- Service-related features
- Average customer spending

These features help represent customer behavior more effectively.

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Converting columns to appropriate data types
- Encoding categorical variables
- Handling unknown categories
- Feature scaling
- Train-test split
- Handling class imbalance

The dataset was divided into training and testing sets using a **stratified train-test split**.

---

## 🧠 Artificial Neural Network

An Artificial Neural Network was developed for binary classification.

### Model Architecture

```text
Input Layer
     ↓
Dense Layer — 64 neurons — ReLU
     ↓
Dense Layer — 32 neurons — ReLU
     ↓
Dropout Layer
     ↓
Output Layer — 1 neuron — Sigmoid
```

### Activation Functions

**ReLU**

Used in the hidden layers to introduce non-linearity.

**Sigmoid**

Used in the output layer to produce a probability between 0 and 1 for churn prediction.

---

## 📊 Model Evaluation

The ANN model was evaluated using:

Accuracy: 75.3%
- Precision: 52.4%
- Recall: 76.7%
- F1 Score: 62.3%
- ROC-AUC: 84.0%
- Threshold: 0.5

Threshold tuning was also performed to understand how changing the classification threshold affects churn prediction.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook
- Git & GitHub

---

## 📁 Project Structure

```text
CUSTOMER-CHURN/
│
├── customer churn.ipynb
├── Raw dataset
└── README.md
```

---

## 👨‍💻 Author

**Rakib Khan**

BCA Graduate | Data Science & AI/ML Learner
