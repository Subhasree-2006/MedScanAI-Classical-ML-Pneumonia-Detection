# 🩺 MedScanAI: Classical Machine Learning Approach for Pneumonia Detection

An explainable **Classical Machine Learning** framework for automated **Pneumonia Detection** from Chest X-ray images using **Local Binary Pattern (LBP)** feature extraction, **XGBoost** classification, and **SHAP Explainable AI**.

---

# 📌 Project Overview

Pneumonia is one of the leading respiratory diseases worldwide. Early diagnosis is essential for effective treatment, but manual interpretation of chest X-ray images is time-consuming and depends on expert radiologists.

This project proposes an **Explainable Classical Machine Learning Framework** that detects pneumonia from chest X-ray images using handcrafted image features instead of deep learning. The framework compares multiple preprocessing methods, feature extraction techniques, dimensionality reduction approaches, and machine learning classifiers to identify the most effective pipeline.

---

# 🎯 Objectives

* Detect pneumonia from chest X-ray images.
* Compare Histogram Equalization and CLAHE preprocessing.
* Compare HOG and LBP feature extraction.
* Compare PCA, LDA and SelectKBest.
* Evaluate Logistic Regression, Random Forest, SVM and XGBoost.
* Handle class imbalance using SMOTE.
* Explain model predictions using SHAP.

---

# 📂 Dataset

**Dataset:** Chest X-ray Pneumonia Dataset

**Source:** Kaggle

Classes:

* Normal
* Pneumonia

Dataset Statistics

| Category | Images |
| -------- | -----: |
| Training |   5216 |
| Testing  |    624 |
| Classes  |      2 |

---

# ⚙️ Technologies Used

* Python
* Google Colab
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* SHAP
* Joblib

---

# 🔬 Methodology

Chest X-ray Images

↓

Image Preprocessing

* Resize (128×128)
* Histogram Equalization

↓

Feature Extraction

* Histogram of Oriented Gradients (HOG)
* Local Binary Pattern (LBP)

↓

Feature Scaling

* StandardScaler

↓

Feature Optimization

* PCA
* LDA
* SelectKBest

↓

Machine Learning Models

* Logistic Regression
* Random Forest
* Support Vector Machine
* XGBoost

↓

Performance Evaluation

↓

Explainability using SHAP

---

# 📊 Experiments Performed

✅ Histogram Equalization vs CLAHE

✅ HOG vs LBP

✅ HOG + LBP

✅ PCA vs LDA

✅ SelectKBest Feature Selection

✅ Logistic Regression

✅ Random Forest

✅ Support Vector Machine

✅ SMOTE-SVM

✅ XGBoost

✅ Cross Validation

✅ ROC Curve

✅ Confusion Matrix

✅ SHAP Explainability

---

# 📈 Experimental Results

| Experiment                                 | Accuracy (%) |
| ------------------------------------------ | -----------: |
| Logistic Regression                        |        72.60 |
| Random Forest                              |        62.82 |
| SVM                                        |        73.08 |
| SMOTE SVM                                  |        73.72 |
| XGBoost (HOG)                              |        74.20 |
| LDA + Logistic Regression                  |        71.63 |
| HOG + SelectKBest + PCA                    |        70.67 |
| HOG + LBP + XGBoost                        |        70.83 |
| CLAHE + LBP + XGBoost                      |        70.03 |
| **Histogram Equalization + LBP + XGBoost** |  **75.80** ⭐ |

---

# 🏆 Best Model

**Pipeline**

Histogram Equalization

↓

Local Binary Pattern (LBP)

↓

StandardScaler

↓

XGBoost

↓

SHAP Explainability

**Best Accuracy:** **75.80%**

---

# 📁 Repository Structure

```text
MedScanAI-Classical-ML-Pneumonia-Detection
│
├── notebooks/
├── figures/
├── models/
├── report/
├── results/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🚀 Installation

```bash
git clone https://github.com/<your-username>/MedScanAI-Classical-ML-Pneumonia-Detection.git
cd MedScanAI-Classical-ML-Pneumonia-Detection
pip install -r requirements.txt
```

---

# ▶️ Running the Project

1. Open the notebook in Google Colab.
2. Upload `kaggle.json`.
3. Download the dataset automatically.
4. Run all notebook cells in order.
5. View evaluation metrics and SHAP plots.

---

# 🔮 Future Work

* Multi-class lung disease classification
* External clinical dataset validation
* Comparison with deep learning models
* Deployment as a web application
* Clinical decision-support integration

---

# 👥 Contributors

**Subha Sree M**

B.Tech Bioinformatics

SASTRA Deemed University

---

**Twinkle Jayasankari S**

B.Tech Bioinformatics

SASTRA Deemed University

---

# 📄 License

This project is distributed under the **MIT License**.

---

# ⭐ If you found this project useful

Please consider giving this repository a **star**.
