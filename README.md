# 🍷 Wine Quality Binary Classification

This project focuses on classifying red wine samples as *Good* or *Bad* based on physicochemical features using machine learning and deep learning models.

## 📊 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Data:** Red wine quality data with 1599 rows and 12 columns
- **Target:** Binary classification: Quality >= 6 → Good (1), else Bad (0)

## 🧠 Models Used
- **Random Forest** (Scikit-learn)
- **K-Nearest Neighbors (KNN)** (Scikit-learn)
- **GRU Neural Network** (TensorFlow/Keras)

## 🔍 Key Features
- 10-Fold Stratified Cross-Validation
- Manual evaluation metric computation (Accuracy, F1, Recall, Precision, TSS, HSS)
- StandardScaler normalization
- Comparison of classical ML vs. DL performance
- Implemented in both `.ipynb` and `.py` formats

## 🛠️ Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow/Keras
- Jupyter Notebook

## ▶️ How to Run
1. Place `winequality-red.csv` in your working directory.
2. Open `kollikonda_dathwik_finalproject.ipynb` or run `kollikonda_dathwik_finalproject.py`
3. The code will:
   - Preprocess the data
   - Train all three models using stratified 10-fold CV
   - Output evaluation metrics for each model

## 📈 Sample Results
| Metric     | Random Forest | KNN    | GRU    |
|------------|---------------|--------|--------|
| Accuracy   | 0.8280        | 0.7336 | 0.7505 |
| F1 Score   | 0.8387        | 0.7592 | 0.7621 |
| TSS        | 0.6546        | 0.4591 | 0.5010 |

## Author
Dathwik Kollikonda
