# Predicting Stress Level Based on Sleep and Lifestyle Habits

Machine learning project for predicting stress levels using sleep patterns and lifestyle-related variables.  
This project includes data preprocessing, exploratory data analysis (EDA), model comparison, hyperparameter tuning, cross-validation, and feature importance analysis.

---

## 📌 Project Overview

Stress is a complex condition influenced by multiple physiological and lifestyle-related factors.

This project aims to predict stress levels using machine learning models trained on sleep and health-related data.

### 🎯 Target Variable
- **Stress Level** (Classification)

### 📥 Input Features
- Sleep Duration
- Sleep Quality
- Physical Activity Level
- Heart Rate
- BMI Category
- Blood Pressure
- Daily Steps
- Occupation
- Demographic Variables

---

## 🧠 Machine Learning Workflow

1. Data Loading  
2. Data Preprocessing  
   - Missing value handling  
   - Encoding categorical variables  
   - Feature scaling (StandardScaler)  
3. Train-Test Split (80% / 20%)  
4. Model Training  
   - Logistic Regression  
   - Support Vector Machine (SVM)  
   - K-Nearest Neighbors (KNN)  
   - Random Forest  
5. Model Evaluation (Accuracy & Weighted F1-score)  
6. Hyperparameter Optimization (GridSearchCV)  
7. 5-Fold Cross Validation  
8. Feature Importance Analysis  
9. Final Model Evaluation (Confusion Matrix & Classification Report)

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 0.92 |
| KNN | 0.92 |
| SVM | 0.97 |
| Random Forest | 0.97 |

After hyperparameter tuning using **GridSearchCV**, the optimized Random Forest model achieved:

- Cross-validation accuracy ≈ 0.96  
- Test accuracy: **100%**

---

## 🔍 Key Findings

Feature importance analysis revealed that:

- Sleep Duration  
- Sleep Quality  
- Heart Rate  

are the most influential predictors of stress levels.

Results indicate that sleep-related variables have a strong impact on stress prediction.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- GridSearchCV  
- K-Fold Cross Validation  

---

## ▶ How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Create virtual environment (Recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
AppliedInformaticsProject.ipynb
```

Run all cells sequentially.

---

## 📁 Dataset

Synthetic sleep health & lifestyle dataset used for stress level prediction.

---

## 🎯 Purpose

This project demonstrates an end-to-end machine learning pipeline for stress level classification and explores the relationship between sleep patterns, lifestyle habits, and mental health.

It showcases:

- Applied machine learning techniques  
- Model comparison and evaluation  
- Hyperparameter tuning  
- Cross-validation  
- Feature importance analysis  
