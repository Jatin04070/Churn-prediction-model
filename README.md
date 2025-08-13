# 📞 Telecom Customer Churn Prediction

## 📌 Overview
This project predicts whether a customer will **churn** (leave the telecom service) based on their account and service usage data.  
Churn prediction helps telecom companies identify at-risk customers and take proactive steps to retain them.

## 🗂 Dataset
- **Source**: Public telecom churn dataset (can be replaced with your own)
- **Size**: ~7,000+ customer records
- **Features**: Demographics, account information, service usage, and payment details
- **Target**: `Churn` (Yes/No)

## 🔍 Project Workflow
1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Feature scaling for numerical data  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of churned vs non-churned customers  
   - Correlation heatmap  
   - Service usage patterns  

3. **Model Training**  
   Implemented and compared multiple ML algorithms:
   - Random Forest Classifier
   - Logistic Regression
   - Support Vector Classifier (SVC)
   - K-Nearest Neighbors (KNN)
   - Gradient Boosting Classifier

4. **Model Evaluation**  
   Models were evaluated using **accuracy score** and cross-validation.

## 📊 Results

| Model                  | Accuracy  |
|------------------------|-----------|
| Random Forest          | 86.65%    |
| Logistic Regression    | 81.10%    |
| SVC                    | 80.35%    |
| KNN                    | 83.00%    |
| Gradient Boosting      | 86.75%    |

✅ **Best Model:** Gradient Boosting (86.75% accuracy)

## 🛠 Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Environment**: Jupyter Notebook

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Jatin04070/Churn-prediction-model.git
