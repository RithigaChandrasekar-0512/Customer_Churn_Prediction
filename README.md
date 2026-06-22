# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn refers to customers who stop using a company's products or services. Predicting customer churn helps businesses identify at-risk customers and take proactive measures to improve customer retention.

This project uses Machine Learning techniques to predict whether a customer is likely to leave a service based on historical customer data.

---

## Objective

* Analyze customer behavior and service usage patterns.
* Predict customer churn using a classification model.
* Identify the most important factors influencing customer churn.

---

## Dataset Features

The dataset contains customer-related information such as:

* Gender
* Senior Citizen Status
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn (Target Variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Google Colab / Jupyter Notebook

---

## Machine Learning Algorithm

### Random Forest Classifier

Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their predictions to improve classification performance.

---

## Project Workflow

1. Load the dataset
2. Explore and understand the data
3. Preprocess categorical features
4. Split the dataset into training and testing sets
5. Train the Random Forest model
6. Predict customer churn
7. Evaluate model performance
8. Analyze feature importance

---

## Results

### Model Performance

* Accuracy: 46.67%

### Most Important Features

1. Monthly Charges
2. Total Charges
3. Tenure
4. Payment Method
5. Tech Support

These features had the highest impact on customer churn prediction.

---

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the Jupyter Notebook or Google Colab file and execute all cells.

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── customer_churn_prediction.ipynb
├── customer_churn_prediction_dataset.csv
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Hyperparameter tuning
* Feature engineering
* Cross-validation
* Testing advanced models such as XGBoost and Gradient Boosting
* Deploying the model using Streamlit or Flask

---

## Author

Rithiga C V

Artificial Intelligence and Data Science Student

Passionate about Machine Learning, Data Science, and AI-driven solutions.
