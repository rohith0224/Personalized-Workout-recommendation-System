# 🏋 Personalized Workout Recommendation System

This project is a **Machine Learning application** designed to provide personalized workout recommendations 
based on an individual's demographic and health information. It combines **multi-output classification** 
with **collaborative filtering** to generate tailored fitness plans.

---

## 📚 Introduction

The system predicts:  
- 🎯 Fitness Goal  
- 🏃‍♂️ Fitness Type  
- 🏋️‍♀️ Exercises  
- 🏋 Equipment  

Additionally, it recommends exercises using **Collaborative Filtering (KNN)** based on similar users.

---

## 📊 Dataset

The dataset includes:  
- Demographic information (Sex, Age, Height, Weight)  
- Health status (Hypertension, Diabetes)  
- Derived metrics (BMI)  
- Target outputs (Goal, Type, Exercises, Equipment)  

Data preprocessing included:  
- One-hot encoding categorical inputs  
- Label encoding target columns  
- Feature scaling with Standard Scaler  
- Train/test split (80/20)  

---

## ⚙ Approach

Steps implemented:  
1. Preprocess categorical and numerical features  
2. Feature scaling with Standard Scaler  
3. Train/test split (80% train, 20% test)  
4. Multi-Output Logistic Regression model  
5. Evaluation with accuracy & classification reports  
6. Collaborative filtering using **K-Nearest Neighbors (KNN)**  
7. Manual user input for real-time predictions  

---

## 🤖 Model Selection

- **Algorithm:** Logistic Regression wrapped with `MultiOutputClassifier`  
- **Why:** Simple, interpretable, and effective for classification  
- **Scaler:** StandardScaler for normalization  
- **Collaborative Filtering:** KNN for exercise recommendations  

---

## 📈 Evaluation

- Accuracy Score per output  
- Classification Report (Precision, Recall, F1-score)  
- Train vs Test Accuracy comparison  

Example performance:  
- Fitness Goal – 100% accuracy  
- Fitness Type – 100% accuracy  
- Exercises – ~100% accuracy  
- Equipment – ~89% accuracy  

---

## 📥 Manual Input Predictions

Users can enter:  
- Sex  
- Age  
- Height & Weight (BMI auto-calculated)  
- Hypertension / Diabetes status  

The system then outputs personalized recommendations and suggests exercises from similar users.

---

## 🛠 Libraries Used

- pandas, numpy  
- scikit-learn (train_test_split, LogisticRegression, MultiOutputClassifier, StandardScaler, LabelEncoder, NearestNeighbors)  

---

## 📂 Project Files

- `PersonalizedWorkoutrecommendatiomSystem.ipynb` – Jupyter Notebook (Google Colab)  
- `gym recommendation.xlsx` – Dataset  

---

## 🚀 Future Improvements

- Add deep learning models (e.g., Neural Networks)  
- Expand dataset with more diverse exercise types  
- Integrate into a web app for user-friendly interface  

🌐 [GitHub](https://github.com/rohith0224) | [LinkedIn](https://linkedin.com/in/)  

