# 🩺 Breast Cancer Classification  

This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset** to classify tumors as **Malignant (M)** or **Benign (B)** based on cell nuclei features extracted from digitized fine needle aspirates (FNA) of breast masses.  

---

## 📂 Dataset Information  

- **Source:**  
  - [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)  
  - Also available at: `ftp.cs.wisc.edu` under `math-prog/cpo-dataset/machine-learn/WDBC/`

- **Attributes:**  
  1. ID number  
  2. Diagnosis (M = malignant, B = benign)  
  3. Features (3–32): Ten real-valued features are computed for each cell nucleus:  
     - Radius (mean of distances from center to points on perimeter)  
     - Texture (standard deviation of gray-scale values)  
     - Perimeter  
     - Area  
     - Smoothness (local variation in radius lengths)  
     - Compactness  
     - Concavity  
     - Concave points  
     - Symmetry  
     - Fractal dimension  

Each feature has mean, standard error, and "worst" (largest) values, leading to 30 real-valued features in total.

---

## 🎯 Objective  

The main goal is to develop a **machine learning model** that can accurately classify breast tumors as **malignant** or **benign**, which is crucial for assisting doctors in early diagnosis and treatment planning.  

---

## ⚙️ Tech Stack  

- **Python** 🐍  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib / Seaborn (for visualization)  
  - Scikit-learn (for ML models)  

---

## 🚀 Workflow  

1. Load and explore the dataset  
2. Preprocess the data (handling missing values, normalization, etc.)  
3. Perform **Exploratory Data Analysis (EDA)**  
4. Train classification models (e.g., Logistic Regression, SVM, Random Forest, etc.)  
5. Evaluate models using metrics like **accuracy, precision, recall, F1-score**  
6. Compare performance and select the best model  

---

## 📊 Expected Output  

- Visualizations of feature distributions and correlations  
- Well-trained classification model  
- Performance metrics and confusion matrix  
- Insights into the most important features for diagnosis  

---

## 📌 References  

- K. P. Bennett and O. L. Mangasarian:  
  *Robust Linear Programming Discrimination of Two Linearly Inseparable Sets*, Optimization Methods and Software 1, 1992, 23-34.  
- [UCI Machine Learning Repository – Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

---

## 📝 License  

This project is released under the [MIT License](LICENSE).  

---
