# Customer Churn Prediction

A machine learning project to predict customer churn using historical customer data. The goal is to identify customers who are likely to leave a service or subscription, enabling proactive retention strategies.

## 📌 Project Overview

Customer churn is when customers stop doing business with a company. Predicting churn helps companies take action before losing valuable customers. This project involves:

- Data preprocessing and exploration
- Feature engineering
- Model training and evaluation
- Deployment-ready prediction pipeline

## 🗂️ Dataset

The dataset used for this project is typically derived from telecom/banking/retail sectors and contains features like:

- Customer demographics
- Account information
- Service usage
- Contract details
- Churn label (Yes/No)

You can download a commonly used dataset from [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn) or use your own dataset.

## ⚙️ Technologies Used

- Python 3.x
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / VS Code
- (Optional) Flask/Streamlit for deployment

## 🧪 Project Structure


## 📊 Exploratory Data Analysis (EDA)

- Handled missing values and outliers
- Visualized churn distribution and correlations
- Converted categorical variables using one-hot encoding or label encoding

## 🤖 Model Building

Multiple models were tested including:

- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machines

The best-performing model was selected based on accuracy, precision, recall, and F1-score.

## 📈 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision & Recall
- ROC-AUC Score

## ✅ Final Model Performance

| Metric       | Score |
|--------------|-------|
| Accuracy     | 0.85  |
| Precision    | 0.79  |
| Recall       | 0.76  |
| F1-Score     | 0.77  |

*(Update with your actual results)*

## 🚀 Deployment

A simple web app was built using Flask/Streamlit to input new customer data and predict churn probability.

To run the app:

```bash
pip install -r requirements.txt
python app.py
