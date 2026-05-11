# Credit Card Fraud Detection using Supervised Machine Learning

A machine learning project focused on detecting fraudulent credit card transactions using multiple supervised learning algorithms and comparing their performance across key evaluation metrics.

---

## Project Overview

Credit card fraud is a major challenge in the financial industry due to the extremely imbalanced nature of transaction datasets. In this project, multiple supervised machine learning models were trained and evaluated to identify fraudulent transactions from legitimate ones.

The primary objective of this project was to:
- Build fraud detection models using different machine learning algorithms
- Compare model performance using classification metrics
- Determine which algorithm performs best for fraud detection

---

## Machine Learning Models Used

The following supervised learning algorithms were implemented and compared:

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression

---

## Evaluation Metrics and Analysis

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

## Dataset

This project uses the publicly available Credit Card Fraud Detection dataset from Kaggle.

### Dataset Characteristics
- Highly imbalanced dataset
- Transactions made by European cardholders
- Fraudulent transactions represent a very small percentage of total transactions
- Features are anonymized using PCA transformation

Dataset link:  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


---

## Results

The following results were obtained from the trained machine learning models:

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Decision Tree | 99.92% | 81.29% | 76.36% | 78.75% |
| Random Forest | 99.96% | 98.68% | 76.53% | 86.21% |
| Logistic Regression | 93.40% | 95.70% | 90.82% | 93.19% |
| KNN | 99.96% | 86.57% | 85.29% | 85.93% |
| SVM | 94.93% | 100.00% | 86.11% | 92.54% |

### Key Findings

- **Random Forest** achieved the highest overall accuracy among the models.
- **SVM** achieved perfect precision, meaning it produced virtually no false positives.
- **Logistic Regression** achieved the highest F1 Score, demonstrating strong balance between precision and recall.
- **KNN** performed consistently well across all metrics.
- ROC curves, AUC scores, and confusion matrices were used to further evaluate classification performance and compare model effectiveness visually.

In fraud detection, accuracy alone can be misleading, since a model can get 99% accuracy simply by predicting “not fraud” most of the time.
What matters more is how many fraud cases you successfully catch (Recall), how many flagged fraud cases are actually fraud (Precision), and the F1 score, which is a balance between precision and recall. 

Although Random Forest and KNN achieved extremely high accuracy, Logistic Regression and SVM demonstrated stronger fraud detection capability through higher recall and F1 scores. Logistic Regression achieved the best overall balance between identifying fraudulent transactions and minimizing classification errors, making it the strongest-performing model for this use case.

The Logistic Regression model was able to catch 90.82% of fraud cases, the highest in all models. Its lower accuracy is likely because it predicts fraud more aggressively, increasing false positives, but catching more real fraud.

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

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

---

## Project Workflow

1. Data preprocessing
2. Exploratory data analysis and visualization
3. Feature scaling and normalization
4. Handling class imbalance
5. Model training
6. Model evaluation and comparison
7. Visualization of ROC curves and confusion matrices
8. Performance analysis across all algorithms



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
