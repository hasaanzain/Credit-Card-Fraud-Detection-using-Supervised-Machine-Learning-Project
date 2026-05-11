# Credit Card Fraud Detection using Supervised Machine Learning

A machine learning project focused on detecting fraudulent credit card transactions using multiple supervised learning algorithms and comparing their performance across key evaluation metrics.

---

## 📌 Project Overview

Credit card fraud is a major challenge in the financial industry due to the extremely imbalanced nature of transaction datasets. In this project, multiple supervised machine learning models were trained and evaluated to identify fraudulent transactions from legitimate ones.

The primary objective of this project was to:
- Build fraud detection models using different machine learning algorithms
- Compare model performance using classification metrics
- Determine which algorithm performs best for fraud detection

---

## 🧠 Machine Learning Models Used

The following supervised learning algorithms were implemented and compared:

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression

---

## 📊 Evaluation Metrics and Analysis

Each model was evaluated and compared using multiple classification and performance metrics, including:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curves
- AUC Scores
- Confusion Matrices

Performance comparisons and visualizations were used to analyze how effectively each model detected fraudulent transactions while minimizing false positives and false negatives.

---

## 📂 Dataset

This project uses the publicly available Credit Card Fraud Detection dataset from Kaggle.

### Dataset Characteristics
- Highly imbalanced dataset
- Transactions made by European cardholders
- Fraudulent transactions represent a very small percentage of total transactions
- Features are anonymized using PCA transformation

Dataset link:  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

---

## 🔍 Project Workflow

1. Data preprocessing
2. Exploratory data analysis and visualization
3. Feature scaling and normalization
4. Handling class imbalance
5. Model training
6. Model evaluation and comparison
7. Visualization of ROC curves and confusion matrices
8. Performance analysis across all algorithms

---

## 📈 Results

The models were compared using classification metrics and visualization techniques to determine which algorithm performed best for fraud detection.

The project demonstrates how different machine learning algorithms behave on highly imbalanced fraud detection datasets and highlights the importance of metrics such as recall, F1 score, ROC-AUC, and confusion matrices when evaluating fraud detection systems.

Key analyses included:
- ROC curve comparison across all models
- AUC score evaluation
- Confusion matrix visualization
- Metric comparison plots

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/hasaanzain/Credit-Card-Fraud-Detection-using-Supervised-Machine-Learning-Project.git
```

### 2. Navigate into the project folder

```bash
cd Credit-Card-Fraud-Detection-using-Supervised-Machine-Learning-Project
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open the Jupyter Notebook and run all cells.

```bash
jupyter notebook
```

---

## 📷 Visualizations Included

The project includes:
- Fraud vs non-fraud transaction distribution plots
- Correlation heatmaps
- Model comparison bar charts
- ROC curves
- AUC score analysis
- Confusion matrices
- Performance metric visualizations

---

## 🎯 Key Learnings

- Handling highly imbalanced datasets
- Comparing multiple supervised learning algorithms
- Evaluating classification models beyond accuracy
- Understanding real-world fraud detection challenges
- Applying preprocessing and feature scaling techniques
- Using ROC curves and AUC scores for model evaluation
- Interpreting confusion matrices for classification analysis

---

## 📚 References

- Kaggle Credit Card Fraud Detection Dataset
- Scikit-learn Documentation
- Imbalanced-learn Documentation

---

## 👨‍💻 Author

Hasaan Mohsin

Physics & Astronomy Graduate | AI & Data Science Enthusiast | Aspiring Astronaut

GitHub: https://github.com/hasaanzain

---

## ⭐ Future Improvements

- Implement XGBoost and LightGBM
- Apply SMOTE oversampling
- Build a real-time fraud detection API
- Deploy using Streamlit or Flask
- Explore deep learning approaches
