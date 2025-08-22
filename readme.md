# 🩺 Pima Indians Diabetes Prediction  

This repository contains a complete machine learning pipeline for predicting diabetes using the **Pima Indians Diabetes dataset**. The notebook walks through **data exploration, preprocessing, model training, and evaluation** with both baseline and ensemble methods.  

---

## 📌 Project Overview  
The primary goal of this project is to predict whether a patient has diabetes based on diagnostic measurements. We use classical supervised learning techniques along with ensemble methods such as **Random Forest, AdaBoost, and Gradient Boosting**.  

**Key steps covered in the notebook:**  
1. **Exploratory Data Analysis (EDA):**  
   - Distribution of features  
   - Identifying missing/invalid values (e.g., zeros in medical features)  
   - Feature-target relationship visualization  

2. **Data Cleaning & Preprocessing:**  
   - Handling biologically invalid zero values by imputing median values  
   - Standardization/Normalization of features  

3. **Model Training & Evaluation:**  
   - Baseline models: Logistic Regression, Decision Tree, KNN, SVM  
   - Ensemble models: Random Forest, AdaBoost, Gradient Boosting  
   - Metrics: Accuracy, Classification Report, ROC-AUC  

4. **Model Comparison & Insights:**  
   - Performance comparison across models  
   - ROC curves for ensemble methods  

---

## 📂 Dataset  
- **Name:** Pima Indians Diabetes Database  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- **Features:** Medical predictor variables (e.g., Glucose, Blood Pressure, BMI, Insulin)  
- **Target:** `Outcome` (0 = Non-diabetic, 1 = Diabetic)  

---

## ⚙️ Installation & Requirements  
Clone the repository and install dependencies:  

```bash
git clone https://github.com/sk-suchi/pima-diabetes-prediction.git
cd pima-diabetes-prediction
pip install -r requirements.txt
```

## 📦 Main libraries used
- numpy  
- pandas  
- matplotlib / seaborn  
- scikit-learn  

---

## 🚀 Usage
Run the Jupyter Notebook:

```bash
jupyter notebook project-pima-indians-diabetes-dataset.ipynb
```