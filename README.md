# Customer Churn Prediction

## 📌 Project Overview
Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a bank (churn) or continue using its services. This helps businesses identify customers at risk and improve customer retention.

---

## 🎯 Objective
- Predict customer churn using machine learning.
- Analyze factors affecting customer retention.
- Improve business decision-making through predictive analytics.

---

## 📂 Dataset
**Dataset Name:** Churn_Modelling.csv

### Features
- RowNumber
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Target Variable)

**Target Variable:**
- `Exited`
  - 0 = Customer Stayed
  - 1 = Customer Left

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Import Dataset
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Prediction

---

## 🤖 Algorithms Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (Optional)
- XGBoost (Optional)

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── churn_prediction.ipynb
├── requirements.txt
├── README.md
└── models/
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Go to the project folder:

```bash
cd customer-churn-prediction
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📌 Results

The model predicts whether a customer will churn based on customer information such as age, balance, geography, credit score, and account activity.

---

## 📷 Sample Output

```
Prediction: Customer will Churn
Probability: 87%
```

or

```
Prediction: Customer will Stay
Probability: 93%
```

---

## 🚀 Future Improvements
- Deploy using Flask or FastAPI
- Build a Streamlit Web Application
- Hyperparameter Tuning
- Add Explainable AI (SHAP)
- Deploy on AWS or Azure

---

## 📚 Learning Outcomes
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Model Building
- Model Evaluation
- Customer Analytics

---

## 👩‍💻 Author

**Sakshi Pabale**

AI & Data Science Student

---

## ⭐ If you like this project, give it a Star!
