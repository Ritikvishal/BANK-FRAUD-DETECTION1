# 💳 Fraud Detection using Machine Learning

## 📘 Project Overview  
This project aims to detect fraudulent financial transactions using **Machine Learning**. By analyzing transaction data, the model identifies patterns and behaviors commonly associated with fraudulent activity. The project leverages data preprocessing, feature selection, and multiple classification algorithms to ensure high accuracy and reliability.

---

## 🧠 Key Features  
- Detects fraudulent transactions using ML models  
- Includes data preprocessing and feature scaling  
- Evaluates performance using Accuracy, Precision, Recall, and F1-Score  
- Visualizes results using Matplotlib and Seaborn  
- Integrates with Power BI for interactive analytics dashboards  

---

## 🧩 Technologies Used  
- **Python 3.x**  
- **Pandas**, **NumPy** – Data manipulation  
- **Matplotlib**, **Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning algorithms  
- **Power BI** – Data visualization  
- **Jupyter Notebook / VS Code** – Development environment


---

## ⚙️ Installation and Setup  

1. **Clone this repository**  
   ```bash
   git clone https://github.com/<your-username>/fraud-detection-ml.git
   cd fraud-detection-ml


---

## 📂 Project Structure  
Fraud-Detection-ML/
│
├── fraudDetectionfile.ipynb # Main ML model implementation
├── bank_transactions_data_2.csv # Dataset used for training/testing
├── fraud_detection.sql # SQL script for data extraction
├── data_power_bi.pbix # Power BI dashboard file
├── README.md # Project documentation
└── requirements.txt # Dependencies list



## ⚙️ Installation and Setup  
1. ****Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/fraud-detection-ml.git
   cd fraud-detection-ml
3. Install required libraries
   pip install -r requirements.txt

4. Run the Jupyter Notebook
   jupyter notebook fraudDetectionfile.ipynb

6. Explore the Power BI Dashboard**
Open data_power_bi.pbix to visualize transaction patterns and fraud insights.

📊 Dataset

The dataset consists of anonymized bank transaction records with attributes such as transaction type, amount, and customer ID, along with labels indicating whether a transaction was fraudulent or legitimate.

🧮 Algorithms Used

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

XGBoost (optional)

Model performances are compared to identify the most effective approach for fraud detection.

📈 Model Evaluation

Evaluation metrics include:

Confusion Matrix

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve

📊 Power BI Dashboard

The Power BI report provides an interactive overview of:

Fraud vs Non-Fraud Transaction counts

Suspicious transaction trends

High-risk customer analysis

🚀 Future Enhancements

Integrate Deep Learning models (ANN, LSTM)

Deploy real-time fraud detection using Flask or FastAPI

Implement live data streaming for real-time prediction
