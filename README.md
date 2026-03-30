![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Project-green)
# 🧪 Molecular Solubility Prediction

A machine learning project to predict **molecular solubility (logS)** using chemical descriptors and regression models.

---

## 📌 Overview

This project builds predictive models to estimate how well a compound dissolves in a solvent — a key property in **drug design and chemistry**.

We use:

* Molecular descriptors (MolWt, LogP, TPSA, etc.)
* Feature engineering + PCA
* Multiple ML models (Ridge, Decision Tree, KNN, Random Forest)

---

## 📊 Dataset

* 📦 ~9,982 compounds
* 🧬 26 features (no missing values)
* 🎯 Target: Solubility (logS)

---

## ⚙️ Models Used

* Linear Regression (Ridge)
* Decision Tree
* K-Nearest Neighbors (KNN)
* 🌲 Random Forest (Best performer)

---

## 🚀 Results

| Model         | RMSE     | R²       |
| ------------- | -------- | -------- |
| Random Forest | **1.08** | **0.78** |

👉 Random Forest performed best using all descriptors.

---

## 🧠 Key Insights

* Higher **hydrophobicity (LogP)** → lower solubility
* Larger molecules → lower solubility
* PCA reduced interpretability and performance

---

## 📁 Project Structure

```
├── Data_Science_project_Final_report.pdf
├── Molecular_solubility_training_results.ipynb
├── curated-solubility-dataset.csv
├── README.md
```

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## 👥 Team

* Vikas
* Ashish
* Sweta
* Shishank

---

## 🔗 Links

* 📄 Report: (add your PDF link)
* 📊 PPT: (add your ppt link)
* 💻 Notebook: (add colab/github link)

---

## ⭐ If you like this project

Give it a star ⭐ and feel free to fork!
