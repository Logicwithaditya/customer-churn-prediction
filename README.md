# 📊 Customer Churn Prediction Project

## 🧠 Overview  
This project predicts whether a telecom customer will **churn (leave the service)** or **stay**, using machine learning techniques.  
It leverages the **Telco Customer Churn dataset** and applies **Logistic Regression** to classify customer behavior based on demographic and service‑related features.

---

## 📁 Dataset  
**File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`  
**Description:**  
Contains customer details such as:  
- Gender, SeniorCitizen, Partner, Dependents  
- Tenure, PhoneService, InternetService, Contract type  
- MonthlyCharges, TotalCharges  
- Churn (Target variable)

---

## ⚙️ Project Workflow  

### 1️⃣ Import Libraries  
Essential Python libraries for data manipulation, preprocessing, and model building:  
pandas, numpy, scikit‑learn (train_test_split, LabelEncoder, StandardScaler, LogisticRegression, metrics)

### 2️⃣ Load Dataset  
Load the dataset and display the first few rows to understand its structure.

### 3️⃣ Data Preprocessing  
- Remove unnecessary columns (`customerID`)  
- Convert `TotalCharges` to numeric and handle missing values  
- Encode categorical variables using `LabelEncoder`

### 4️⃣ Train‑Test Split  
Split the dataset into training and testing sets (80‑20 ratio).

### 5️⃣ Model Training  
Standardize features and train a **Logistic Regression** model with `max_iter=1000`.

### 6️⃣ Evaluation  
Evaluate model performance using accuracy, confusion matrix, and classification report.

---

## 📈 Results  
- **Accuracy:** ~80–85% (depending on preprocessing)  
- **Model:** Logistic Regression  
- **Insights:** Customers with shorter tenure and higher monthly charges are more likely to churn.

---

## 🔮 Sample Prediction  
Predict churn for a sample customer from the test set:  
If prediction = 1 → Customer will **Churn**  
Else → Customer will **Stay**

---

## 🧩 Future Improvements  
- Try other models: Random Forest, XGBoost, or Neural Networks  
- Perform feature selection and hyperparameter tuning  
- Deploy using Flask or Streamlit for interactive prediction  

---

## 🚀 How to Run  

1. **Clone the repository**  
   `git clone https://github.com/<your-username>/customer-churn-prediction.git`

2. **Navigate to the project folder**  
   `cd customer-churn-prediction`

3. **Install dependencies**  
   `pip install -r requirements.txt`

4. **Run the script**  
   `python churn_prediction.py`

---

## 🧾 License  
This project is licensed under the **MIT License**.

---

## 👨‍💻 Author  
**Aditya**  
BCA (AI/ML) Student | Aspiring Data Analyst  
