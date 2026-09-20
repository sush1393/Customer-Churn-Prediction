# Customer Churn Prediction Using Machine Learning

## Author

**Sushma Boreddy**
GitHub: https://github.com/sush1393

---

## Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Churn occurs when customers discontinue a company's services and switch to competitors. Predicting customer churn helps businesses identify customers who are likely to leave and take proactive actions to retain them.

This project uses Machine Learning techniques to predict whether a telecom customer is likely to churn based on customer demographics, account information, and service-related features.

---

## Problem Statement

The objective of this project is to build a Machine Learning model that predicts customer churn in a telecom company.

By identifying customers who are at risk of leaving, businesses can:

* Improve customer retention
* Reduce revenue loss
* Offer personalized retention plans
* Enhance customer satisfaction
* Support data-driven decision making

---

## Dataset

**Dataset Name:** Telco Customer Churn Dataset

**Source:** Kaggle

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### Dataset Features

| Feature         | Description                         |
| --------------- | ----------------------------------- |
| customerID      | Unique customer identifier          |
| gender          | Customer gender                     |
| SeniorCitizen   | Senior citizen status               |
| Partner         | Whether the customer has a partner  |
| Dependents      | Whether the customer has dependents |
| tenure          | Number of months with the company   |
| PhoneService    | Phone service subscription          |
| InternetService | Internet service type               |
| Contract        | Contract type                       |
| PaymentMethod   | Payment method used                 |
| MonthlyCharges  | Monthly bill amount                 |
| TotalCharges    | Total amount charged                |
| Churn           | Target variable                     |

### Target Variable

**Churn**

* Yes → Customer leaves the company
* No → Customer remains with the company

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Project Workflow

### 1. Data Collection

* Downloaded the Telco Customer Churn Dataset from Kaggle.
* Loaded the dataset into Google Colab using Pandas.

### 2. Data Preprocessing

* Removed unnecessary columns such as `customerID`.
* Handled missing values in the dataset.
* Converted data types where necessary.
* Encoded categorical variables using Label Encoding.

### 3. Exploratory Data Analysis (EDA)

Performed data visualization and analysis to understand customer behavior and churn patterns.

Key analyses included:

* Churn distribution
* Customer tenure analysis
* Monthly charges distribution
* Feature importance analysis

### 4. Model Building

The dataset was split into training and testing sets.

Machine Learning Model Used:

* Random Forest Classifier

### 5. Model Evaluation

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Feature Importance Analysis

---

## Machine Learning Algorithm

### Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction performance and reduce overfitting.

Benefits:

* High accuracy
* Handles large datasets effectively
* Works well with both numerical and categorical features
* Provides feature importance information

---

## Results

The trained model successfully predicts customer churn based on customer-related features.

### Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

**Expected Accuracy:** Approximately 80% (may vary depending on preprocessing and train-test split)

---

## Visualizations

### Confusion Matrix

The confusion matrix helps evaluate classification performance by comparing actual and predicted values.

Add your generated image here:

```text
images/confusion_matrix.png
```

### Feature Importance

Feature importance analysis identifies the most influential factors affecting customer churn.

Add your generated image here:

```text
images/feature_importance.png
```

---

## Project Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── confusion_matrix.png
    └── feature_importance.png
```

---

## Installation and Usage

### Clone the Repository

```bash
git clone https://github.com/sush1391/customer-churn-prediction.git
```

### Navigate to the Project Directory

```bash
cd customer-churn-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the notebook using:

* Google Colab
* Jupyter Notebook

and execute all cells sequentially.

---

## Future Enhancements

* Hyperparameter tuning for improved accuracy
* XGBoost and Gradient Boosting implementation
* Customer retention recommendation system
* Interactive dashboard development
* Deployment using Streamlit or Flask
* Real-time churn prediction system

---

## Business Impact

This project can help telecom companies:

* Identify customers likely to churn
* Improve retention strategies
* Reduce customer acquisition costs
* Increase customer lifetime value
* Improve overall business profitability

---

## Conclusion

Customer churn prediction is an important business application of Machine Learning. This project demonstrates how customer data can be analyzed and used to build predictive models that help organizations identify customers at risk of leaving.

Using a Random Forest Classifier, the model provides valuable insights into customer behavior and enables businesses to take proactive retention measures, ultimately reducing churn and improving customer satisfaction.

---

## License

This project is developed for educational and learning purposes.
