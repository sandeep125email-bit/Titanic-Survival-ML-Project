# 🚢 Titanic Survival Machine Learning Project

## 📌 Project Overview
This project focuses on predicting passenger survival on the Titanic using Machine Learning techniques.  
Multiple classification algorithms were applied and compared to identify which model performs best for this dataset.

The project demonstrates a complete end-to-end Machine Learning workflow including data preprocessing, model training, evaluation, and performance comparison.

---

## 🎯 Objective
- Apply multiple Machine Learning algorithms on a single dataset
- Compare model performance using accuracy metrics
- Identify the best-performing model
- Understand how algorithm choice affects prediction results

---

## 📂 Dataset
**Titanic Survival Dataset (Kaggle)**

The dataset contains passenger information such as:
- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Fare
- Number of family members onboard
- Port of Embarkation
- Survival Status (Target Variable)

Prediction Goal:
👉 Predict whether a passenger survived (1) or not (0).

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Handling missing values (Age, Embarked)
- Removing irrelevant columns (PassengerId, Name, Ticket, Cabin)
- Encoding categorical variables
- Feature preparation

### 2️⃣ Model Training
The following Machine Learning algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

### 3️⃣ Model Evaluation
- Accuracy comparison across models
- Identification of best-performing algorithm

---

## 🧠 Algorithms Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

---

## 📊 Results
Each algorithm produced different accuracy values, demonstrating that model performance depends on algorithm design and learning capability even when the dataset remains the same.

The experiment helped determine the most suitable algorithm for the Titanic survival prediction problem.

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle Notebook

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/sandeep125email-bit/Titanic-Survival-ML-Project.git
