# 🎗️ Prediction of PCR and RFS using Machine Learning for Breast Cancer

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/varshawali/Prediction-of-PCR-and-RFS-using-Machine-Learning-for-Breast-cancer/blob/main/notebook.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Machine learning models to predict **Pathological Complete Response (PCR)** and **Relapse-Free Survival (RFS)** in breast cancer patients, enabling earlier clinical decision-making.

---

## 🩺 Problem Statement

Breast cancer is the most common cancer among women globally. Two critical clinical outcomes are:

- **PCR (Pathological Complete Response)**: Whether a patient shows no residual cancer after chemotherapy — a strong predictor of long-term survival.
- **RFS (Relapse-Free Survival)**: Whether cancer returns after initial treatment.

Predicting these outcomes early allows oncologists to personalise treatment plans and improve patient prognosis.

---

## 🧠 Approach

Multiple ML classifiers were trained and compared on clinical and molecular features:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Neural Network (MLP)

Features used include tumour grade, hormone receptor status, HER2 status, tumour size, and gene expression data.

---



---

## 🗃️ Dataset

Data sourced from publicly available breast cancer datasets:
- [METABRIC Dataset](https://www.cbioportal.org/study/summary?id=brca_metabric)
- [TCGA Breast Cancer](https://portal.gdc.cancer.gov/)

> Please download the data separately and place it in the `/data` folder before running the notebooks.

---

## 🛠️ Setup & Usage

```bash
git clone https://github.com/varshawali/Prediction-of-PCR-and-RFS-using-Machine-Learning-for-Breast-cancer.git
cd Prediction-of-PCR-and-RFS-using-Machine-Learning-for-Breast-cancer
pip install -r requirements.txt
jupyter notebook
```

Or run directly in your browser:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/varshawali/Prediction-of-PCR-and-RFS-using-Machine-Learning-for-Breast-cancer/blob/main/notebook.ipynb)

---

## 📁 Project Structure

```
├── data/                   # Raw and preprocessed datasets
├── notebooks/
│   ├── EDA.ipynb           # Exploratory data analysis
│   ├── PCR_prediction.ipynb
│   └── RFS_prediction.ipynb
├── models/                 # Saved model files
├── requirements.txt
└── README.md
```

---

## 🔖 Topics

`machine-learning` `breast-cancer` `healthcare-ai` `classification` `xgboost` `random-forest` `python` `jupyter-notebook`

---

## ⚠️ Disclaimer

This project is for **research and educational purposes only**. It is not intended for clinical use or medical diagnosis.

---

## 📬 Contact

**Varsha Wali** — [LinkedIn](https://www.linkedin.com/in/varshawali) · [GitHub](https://github.com/varshawali)
