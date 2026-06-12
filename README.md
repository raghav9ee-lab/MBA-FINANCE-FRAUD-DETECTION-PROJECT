## 🎯 Business Problem

Financial fraud is a major challenge for banks, fintech companies, and payment service providers. Fraudulent transactions can lead to significant financial losses and damage customer trust.

The goal of this project is to build a predictive model that can classify transactions as:

- Legitimate Transaction (0)
- Fraudulent Transaction (1)

---

## 🛠️ Tools & Technologies

### Analytics & Data Science
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

### No-Code / Low-Code Tools
- Orange Data Mining
- n8n Workflow Automation

### Version Control
- Git
- GitHub

---

## 📂 Project Structure


MBA-Finance-Fraud-Detection-Project
│
├── Dataset
│   ├── fraud_detection_dataset.csv
│
├── Notebooks
│   ├── EDA.ipynb
│   ├── Data_Cleaning.ipynb
│   ├── Model_Building.ipynb
│
├── Reports
│   ├── Project_Report.pdf
│
├── Images
│   ├── dashboard.png
│   ├── confusion_matrix.png
│
├── README.md


---

## 📊 Dataset Information

The dataset contains financial transaction records with attributes such as:

| Feature | Description |
|----------|-------------|
| Transaction_ID | Unique transaction identifier |
| User_ID | Customer identifier |
| Transaction_Amount | Amount transferred |
| Transaction_Type | Payment category |
| Payment_Method | UPI/Card/Net Banking |
| Transaction_Time | Date & Time |
| Location | Transaction location |
| Device_Type | Device used |
| Previous_Fraud_Flag | Historical fraud indicator |
| Fraud_Label | Target Variable |

---

## 🔍 Exploratory Data Analysis (EDA)

Key analyses performed:

- Missing Value Analysis
- Outlier Detection
- Transaction Amount Distribution
- Fraud vs Non-Fraud Comparison
- Correlation Analysis
- Payment Method Analysis
- User Behavior Analysis

---

## 🤖 Machine Learning Models

The following models can be used for fraud detection:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost
5. Gradient Boosting

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

---

## 📈 Sample Workflow

1. Load Dataset
2. Clean Missing Values
3. Encode Categorical Variables
4. Split Training & Testing Data
5. Train Machine Learning Model
6. Predict Fraud Transactions
7. Evaluate Model Performance
8. Generate Business Insights

---

## 🚨 Fraud Detection Logic

A transaction may be flagged if:

- Transaction amount exceeds threshold
- Unusual transaction location
- High transaction frequency
- New device login
- Historical fraud pattern detected

Example:

python
if transaction_amount > 36000:
    alert = "High Risk Transaction"


---

## 📊 Expected Outcomes

- Identify high-risk transactions
- Reduce financial fraud losses
- Improve fraud monitoring process
- Support decision-making for finance teams

---

## 📚 Finance Concepts Applied

- Risk Management
- Financial Analytics
- Fraud Analytics
- Transaction Monitoring
- Predictive Analytics
- Data-Driven Decision Making

---

## 🚀 Future Enhancements

- Real-Time Fraud Detection
- Dashboard Development
- API Integration
- n8n Automation Workflow
- AI-Based Fraud Monitoring
- Explainable AI (XAI)

---

## 👨‍🎓 Academic Purpose

This project was developed as part of MBA Finance learning to understand:

- Financial Data Analytics
- Machine Learning Applications in Finance
- Fraud Detection Systems
- Business Intelligence

---

## 👤 Author

RAGHAV SHARMA

MBA (Finance)

---

## ⭐ If you found this project useful

Please consider giving the repository a Star ⭐
![n8n Workflow Structure](images/n8nworkflow.png.jpeg)
![Financial Risk Alert Email](images/FinancialRiskAlert.jpg.jpeg)
![High Risk Fraud Alert Email](images/HighRiskFraudAlert.jpg.jpeg)
![High Value CFO Alert Email](images/HIGHVALUE.jpg.jpeg)
![Loan Approval Auto Rejection Email](images/LOANAPPROVEMENT.jpg.jpeg)
