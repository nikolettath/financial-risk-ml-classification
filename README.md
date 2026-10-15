# Financial Risk Assessment & Classification 

This repository contains a Machine Learning project focused on predicting customer **Risk Rating** (Low, Medium, High) based on financial and demographic data. More specifically, the project explores and compares various Machine Learning algorithms to evaluate financial risk. It includes data preprocessing, exploratory data analysis (EDA), dimensionality reduction, and classification models. The project consists of a single Jupyter Notebook containing the full analysis, code, and visualizations.

* **Dataset:** Financial Risk Dataset (15,000 samples, 10 numerical features).
* **Problem Type:** Multiclass Classification (3 classes).

### Techniques & Models
* **Data Preprocessing & Normalization:** Handling missing values and feature scaling.
* **Exploratory Data Analysis (EDA):** Class distribution and correlation analysis using Seaborn & Matplotlib.
* **Dimensionality Reduction:** Principal Component Analysis (PCA) via Singular Value Decomposition (SVD).
* **Classification Algorithms:** Comparison across multiple models (including Logistic Regression, SVM, KNN, MLP, Naive Bayes, etc.).

### Conclusion & Key Findings
* **Optimal Models:** Logistic Regression and SVM achieved the highest test accuracy (59.30%), proving that the financial dataset features are predominantly linearly separable.
* **Model Complexity vs. Performance:** Complex models like the Multilayer Perceptron (MLP) did not outperform simpler linear methods, while K-Nearest Neighbors (KNN) suffered from overfitting due to noise and sensitivity to outliers.
* **Takeaway:** For this specific financial risk assessment task, simpler linear models provide the best balance of maximum accuracy and minimal computational complexity.
