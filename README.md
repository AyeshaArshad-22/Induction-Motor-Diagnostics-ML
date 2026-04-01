# Induction Motor Fault Diagnosis Suite

## 🎯 Overview
This repository contains a comprehensive collection of machine learning research and implementations focused on **Condition Monitoring** and **Fault Diagnosis** of three-phase induction motors. By utilizing **Current Signature Analysis (CSA)**, these projects demonstrate how to identify mechanical degradation through high-frequency electrical sensor data.

---

## 🚀 Projects Included

### 1. Efficient Fault Diagnosis using Custom k-NN and PCA
* **Methodology:** Implementation of a "from-scratch" K-Nearest Neighbors algorithm combined with Principal Component Analysis.
* **Key Insight:** Successfully reduced 1,000-sample raw signal blocks into 30 principal components while maintaining **99.94% of data variance**.
* **Performance:** Achieved an optimized accuracy of **97.98%** at $K=7$.

### 2. Induction Motor Fault Analysis via Current Signatures
* **Methodology:** Logistic Regression framework for 14-class diagnostic classification.
* **Scope:** Analyzes fault severity levels (0.7mm to 1.7mm) for both inner and outer bearing races, alongside Broken Rotor Bar (BRB) conditions.
* **Objective:** Testing the limits of linear classifiers on high-dimensional, non-linear industrial signal data.

### 3. Smart Motor Diagnostics: A Comparative Study of NB and SVM
* **Methodology:** A rigorous benchmarking between Gaussian Naive Bayes and Support Vector Machines (SVM).
* **Key Insight:** SVM demonstrated superior robustness in handling the complex decision boundaries of 14-class industrial faults.
* **Analysis:** Includes detailed training/validation accuracy and loss curves to evaluate model generalization.

---

## 🛠️ Technical Stack
* **Languages:** Python
* **Tools:** Jupyter Notebooks
* **Core Libraries:** Scikit-Learn, NumPy, Pandas, Matplotlib, Seaborn

---

## ⚙️ Setup & Usage
1. **Clone the Repo:** `git clone https://github.com/yourusername/Induction-Motor-Diagnostics-ML.git`

2. **Data Pathing:** All notebooks are configured to look for datasets in a local `./dataset/` folder. Ensure your CSV files are placed there before running.

3. **Outputs:** The notebooks contain pre-rendered confusion matrices and performance plots for immediate review.

---

## 👤 Author
**Ayesha Arshad** *Department of Data Science, GIFT University*
