## 🩺 Diabetes Prediction using Machine Learning

This project uses the Pima Indians Diabetes Dataset from Kaggle to build a machine learning model that predicts whether a patient is likely to have diabetes based on diagnostic health measurements. The dataset includes medical attributes such as glucose level, BMI, insulin, blood pressure, age, and pregnancy history.
The goal of this project is to apply a complete end-to-end machine learning pipeline including data preprocessing, exploratory data analysis (EDA), model training, and evaluationusing classification metrics to support early diabetes detection.


## 📊 Dataset

- Source: Kaggle  
- Dataset: Pima Indians Diabetes Dataset  
- Link: https://www.kaggle.com/datasets/mathchi/diabetes-data-set  

🎥 Workflow Reference: ML pipeline structure inspired by standard supervised learning workflow

## ⚙️ Tech Stack

- Python 🐍  
- NumPy  
- Pandas   
- Scikit-learn  

## 🔄 Machine Learning Workflow
          ┌─────────────────────┐
          │   Data Collection   │
          │ (Kaggle Dataset)    │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Data Preprocessing  │
          │ - Missing values    │
          │ - Scaling/cleaning  │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Exploratory Data    │
          │ Analysis (EDA)      │
          │ - Correlation       │
          │ - Visualization     │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Train-Test Split    │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Model Training      │
          │ - Logistic Reg.     │
          │ - Random Forest     │
          │ - SVM / others      │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Model Evaluation    │
          │ - Accuracy          │
          │ - Confusion Matrix  │
          │                     |
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Prediction System   │
          │ (New Patient Data)  │
          └─────────────────────┘


## 📈 Models Used

- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  

## 🧪 Evaluation Metrics

- Accuracy Score  
- Precision & Recall  
- Confusion Matrix  

📊 Results

The trained models show strong performance in predicting diabetes risk, with Random Forest / Logistic Regression typically achieving the best balance between accuracy and interpretability.