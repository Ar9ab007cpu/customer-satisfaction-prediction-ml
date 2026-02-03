# Customer Satisfaction Prediction using Machine Learning

This project develops a supervised machine learning pipeline to predict customer satisfaction based on demographic attributes, travel details, and service-related features. The objective is to identify key factors influencing satisfaction and support data-driven service improvements.

---

## Project Overview

Customer satisfaction is a critical performance indicator for service-driven industries such as airlines, hospitality, and transportation. Understanding the drivers of satisfaction enables organizations to enhance customer experience, improve retention, and optimize operational strategies.

This project builds an end-to-end classification workflow that transforms raw customer data into predictive insights.

### Workflow
- Data cleaning and preprocessing  
- Categorical encoding  
- Feature scaling  
- Exploratory Data Analysis  
- Correlation analysis  
- Model training and evaluation  
- Performance comparison  

---

## Dataset

The dataset contains customer travel information along with satisfaction labels.

### Key Features
- Gender  
- Age  
- Customer class  
- Type of travel  
- Flight distance  
- Departure and arrival delays  
- Service-related attributes  

**Target Variable:**  
`satisfied` — Indicates whether a customer is satisfied (1) or not satisfied (0).

---

## Models Implemented

### Random Forest Classifier
An ensemble learning method that combines multiple decision trees to improve predictive performance and reduce overfitting.

### Decision Tree Classifier
A baseline interpretable model used for comparison.

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Log Loss  
- Confusion Matrix  

Using multiple metrics ensures balanced evaluation beyond overall accuracy.

---

## Key Insights

- Ensemble methods demonstrated stronger predictive capability compared to a single decision tree.
- Delay-related features and travel attributes show meaningful influence on satisfaction outcomes.
- Proper preprocessing and feature scaling significantly improve model performance.

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## How to Run the Project

### Clone the repository
```bash
git clone https://github.com/Ar9ab007cpu/customer-satisfaction-prediction-ml.git
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook
```bash
jupyter notebook
```

Open:

```
Customer_Satisfaction_Prediction.ipynb
```

---

## Project Highlights

- Built a complete classification pipeline  
- Applied feature engineering and encoding techniques  
- Compared tree-based models  
- Evaluated performance using multiple metrics  
- Generated actionable insights from customer data  

---

## Future Improvements

- Implement gradient boosting models such as XGBoost or LightGBM  
- Perform hyperparameter tuning  
- Analyze feature importance for deeper business insights  
- Address potential class imbalance  
- Deploy the model as an API for real-time predictions  

---

## Author

Arnab
