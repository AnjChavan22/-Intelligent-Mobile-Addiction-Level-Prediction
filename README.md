# Intelligent Mobile Addiction Level Prediction
Built an end-to-end ML pipeline on a 3,000-row dataset — applied feature engineering, PCA, and StandardScaler, then trained and compared 5 classifiers (Logistic Regression, Decision Tree, Random Forest, SVM, XGBoost) using accuracy, F1-score, and ROC-AUC.

# 📱 Mobile Addiction Level Prediction

Predicts self-reported mobile addiction levels (Low / Moderate / High / Severe) 
using smartphone behavior and psychological data.

## 📊 Dataset
- 3,000 rows, 34 features
- Features include screen time, sleep hours, stress level, anxiety score, gaming hours

## 🛠️ Tech Stack
Python | Pandas | Scikit-learn | XGBoost | Seaborn | Matplotlib

## 🔄 Pipeline
- Exploratory Data Analysis (EDA)
- Feature Engineering (Mental Risk Score, Entertainment Usage)
- Preprocessing: Label Encoding, Standard Scaling, PCA, SelectKBest
- Trained & compared 5 models: Logistic Regression, Decision Tree, Random Forest, SVM, XGBoost
- Evaluated using Accuracy, F1-Score, ROC-AUC, Cross-Validation

## 📁 Files
- `notebook.ipynb` → Full ML pipeline
