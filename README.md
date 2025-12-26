# 💳 Credit Risk Modeling System

Loan Default Prediction & Customer Risk Assessment

📌 Overview

This project is an end-to-end Credit Risk Modeling application that predicts a borrower’s loan default risk and overall creditworthiness using machine learning. It simulates how financial institutions evaluate applicants by combining predictive modeling with explainable insights, delivered through an interactive Streamlit web interface.

The system allows users to input borrower details such as age, income, loan amount, tenure, and credit history, and instantly receive a predicted risk outcome.

🎯 Key Features

* Real-time loan default prediction

* Interactive Streamlit-based UI

* Robust feature preprocessing and scaling

* Production-style model inference using serialized ML models

* Modular prediction logic for maintainability

🧠 Architecture & Workflow

1. User Input (Frontend)

* Streamlit UI collects borrower information (age, income, loan amount, tenure, credit score, etc.)

2. Feature Preparation

* Inputs are validated and transformed into model-ready format

* Feature ordering and scaling handled consistently to match training pipeline

3. Model Inference

* Pre-trained ML model loaded using joblib

* Prediction executed in real time

4. Result Interpretation

* Output displayed as default risk classification

* Designed to integrate explainability layers (e.g., SHAP)

🛠️ Tech Stack

* Programming Language: Python

* Frontend: Streamlit

* Data Processing: Pandas, NumPy

* Machine Learning: Scikit-learn

* Model Persistence: Joblib

* Development Environment: Jupyter Notebook

📂 Project Structure
```bash
ML_project_credit_risk_modeling/
├── .gitignore                  # Git ignore rules
├── README.md                  # Project documentation
├── main.py                    # Streamlit UI & main app logic
├── prediction_helper.py       # Preprocessing & model prediction functions
└── requirements.txt           # Python package requirements

```
▶️ How to Run the Project
1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

2️⃣ Run the Application
```bash
streamlit run main.py
```

3️⃣ Use the App

* Enter borrower details in the UI

* Click Predict

* View loan default risk instantly

📈 Model Details

* Supervised classification model trained on historical credit data

* Designed to handle common financial risk factors

* Can be extended with:

  - XGBoost / Random Forest

  - SHAP explainability

  - Probability calibration

🔍 Key Learning Outcomes

* Built a real-world ML inference pipeline

* Demonstrated deployment-ready ML using Streamlit

* Implemented modular, reusable prediction logic

* Applied ML concepts to financial risk analytics

🚀 Future Enhancements

* Support probability scores instead of binary output

* Integrate cloud deployment (AWS / GCP)

👤 Author

Lalith Kumar Dabilpuram
Data Scientist | Machine Learning | Financial Analytics | GenAI Engineer

Add model versioning and monitoring
