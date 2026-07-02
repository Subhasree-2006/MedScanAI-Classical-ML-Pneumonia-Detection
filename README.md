# 🩺 MedScanAI: Classical Machine Learning Approach for Pneumonia Detection

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-green)
![XGBoost](https://img.shields.io/badge/XGBoost-Classifier-red)
![SHAP](https://img.shields.io/badge/Explainable%20AI-SHAP-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Overview

MedScanAI is an Explainable Classical Machine Learning framework for automated pneumonia detection from chest X-ray images.

Unlike most medical imaging projects that rely on deep learning, this project demonstrates that carefully designed feature engineering combined with machine learning can provide an efficient and interpretable solution.

The project compares multiple preprocessing methods, feature extraction techniques, dimensionality reduction methods, and machine learning classifiers to identify the best-performing pipeline.

---

## 🎯 Objectives

- Detect pneumonia from chest X-ray images.
- Compare Histogram Equalization and CLAHE.
- Compare HOG and Local Binary Pattern (LBP).
- Compare PCA and LDA.
- Evaluate Logistic Regression, Random Forest, SVM, SMOTE-SVM and XGBoost.
- Explain predictions using SHAP.

---

## 📂 Dataset

**Dataset:** Chest X-ray Pneumonia Dataset

**Source:** Kaggle

| Class | Images |
|-------|--------:|
| Normal | 1583 |
| Pneumonia | 4273 |
| Total | 5856 |

---

## 🛠 Technologies

- Python
- Google Colab
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- SHAP
- Joblib

---

# 🔬 Workflow

Chest X-ray Images

↓

Resize (128×128)

↓

Histogram Equalization

↓

Feature Extraction

• HOG

• LBP

↓

StandardScaler

↓

PCA

↓

Machine Learning

• Logistic Regression

• Random Forest

• SVM

• XGBoost

↓

Performance Evaluation

↓

SHAP Explainability

---

# 🧪 Experiments

✔ Histogram Equalization vs CLAHE

✔ HOG vs LBP

✔ HOG + LBP

✔ PCA vs LDA

✔ SelectKBest

✔ Logistic Regression

✔ Random Forest

✔ SVM

✔ SMOTE-SVM

✔ XGBoost

✔ Cross Validation

✔ ROC Curve

✔ SHAP Explainability

---

# 📊 Experimental Results

| Model | Accuracy |
|--------------------------|---------:|
| Logistic Regression | 72.60% |
| Random Forest | 62.82% |
| SVM | 73.08% |
| SMOTE + SVM | 73.72% |
| XGBoost | 74.20% |
| HOG + LBP + XGBoost | 70.83% |
| CLAHE + LBP + XGBoost | 70.03% |
| ⭐ Histogram Equalization + LBP + XGBoost | **75.80%** |

---

# 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Sensitivity
- Specificity
- ROC-AUC
- Confusion Matrix
- SHAP Analysis

---

# 📁 Repository Structure

```
MedScanAI-Classical-ML-Pneumonia-Detection/

│── notebooks/
│   └── MedScanAI_Classical_ML_Pneumonia_Detection.ipynb

│── report/
│   └── MedScanAI_Project_Report.pdf

│── figures/
│   ├── workflow.png
│   ├── histogram_equalization.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── shap_summary.png

│── models/
│   ├── model.pkl
│   ├── scaler.pkl
│   └── pca.pkl

│── results/
│   ├── metrics.csv
│   └── experiments.csv

│── README.md
│── requirements.txt
│── LICENSE
```

---

# ▶️ How to Run

```bash
git clone https://github.com/Subhasree-2006/MedScanAI-Classical-ML-Pneumonia-Detection.git

cd MedScanAI-Classical-ML-Pneumonia-Detection

pip install -r requirements.txt
```

Open the notebook in Google Colab and run all cells.

---

# 🔮 Future Work

- Multi-class lung disease detection
- External clinical dataset validation
- Web application deployment
- Comparison with deep learning models
- Mobile healthcare integration

---

# 👥 Contributors

- **Subha Sree M**
- **Twinkle Jayasankari S**

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful, please consider giving this repository a ⭐ Star.

