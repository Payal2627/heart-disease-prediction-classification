# ❤️ Heart Disease Prediction using Machine Learning Classification

## 📌 Project Overview

This project presents a complete end-to-end machine learning classification workflow for predicting whether a patient has heart disease based on clinical and medical attributes. The project includes data exploration, preprocessing, feature engineering, handling class imbalance using SMOTE, model training, hyperparameter tuning, ensemble learning, and comprehensive performance evaluation.

Five supervised machine learning classification algorithms were implemented and compared to identify the most effective model for heart disease prediction. Additionally, an Ensemble Voting Classifier was developed to combine the strengths of multiple classifiers and improve prediction performance.

---

## 🎯 Objectives

- Understand the Heart Disease dataset
- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the data
- Handle class imbalance using SMOTE
- Train multiple classification models
- Optimize models using GridSearchCV
- Build an Ensemble Voting Classifier
- Compare model performance using evaluation metrics

---

## 📊 Dataset

- **Source:** Kaggle
- **Dataset:** Heart Disease Dataset
- **Problem Type:** Binary Classification
- **Target Variable:** Heart Disease (Presence / Absence)

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 🔍 Exploratory Data Analysis (EDA)

The following preprocessing and analysis steps were performed:

- Data loading
- Dataset inspection
- Missing value analysis
- Duplicate record detection
- Statistical summary
- Data type verification
- Label Encoding of categorical features
- Outlier detection using the IQR method

### Data Visualizations

- Histograms
- Box Plots
- Scatter Plots
- Correlation Heatmap

These visualizations helped identify feature distributions, detect outliers, and understand relationships among variables.

---

## ⚙️ Data Preprocessing

The dataset was prepared using several preprocessing techniques:

- Label Encoding
- Feature Selection
- Train-Test Split
- Feature Scaling using StandardScaler
- Handling Class Imbalance using SMOTE

SMOTE was applied only to the training data to create a balanced dataset and improve model learning.

---

## 🤖 Classification Models Implemented

The following machine learning algorithms were trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Random Forest Classifier
5. Support Vector Machine (SVM)

---

## 🔧 Hyperparameter Tuning

To improve model performance, each classifier was optimized using **GridSearchCV**.

The best hyperparameters were selected through cross-validation and used to train the final models.

---

## 🧠 Ensemble Learning

An Ensemble Learning approach was implemented using a **Voting Classifier**, which combines predictions from:

- Logistic Regression
- KNN
- Decision Tree
- Random Forest
- Support Vector Machine

The final prediction is determined through majority voting, improving the robustness and reliability of the model.

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

These metrics were used to compare the predictive performance of all classifiers.

---

## 🏆 Results

The performance of all individual classifiers and the Ensemble Voting Classifier was compared using multiple evaluation metrics.

The comparison demonstrates how preprocessing, feature scaling, SMOTE, hyperparameter tuning, and ensemble learning contribute to improved prediction accuracy and better generalization.

---

## 📚 Key Learning Outcomes

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Label Encoding
- Standardization
- Handling Imbalanced Data with SMOTE
- Binary Classification
- Hyperparameter Tuning using GridSearchCV
- Ensemble Learning with Voting Classifier
- Model Evaluation and Comparison

---

## 👩‍💻 Author

**Payal Malandkar**

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning | Data Science

---

⭐ If you found this project useful, consider giving it a star.
