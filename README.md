# Credit Card Fraud Detection: A Machine Learning Approach

### Authors
This project was developed by **Lorenzo Zanotti**, **Tommaso Arone**, and **Clelia Meloni**.

---

### 📌 Description
This project was developed as part of the **Machine Learning** course within the **MSc in Data Science** program at the **University of Milano-Bicocca**.

The study focuses on the classification of credit card transactions to identify fraudulent activities. Using a dataset of 1,000,000 transactions, the project addresses the challenges of highly imbalanced data (only 8.7% of transactions are fraudulent) to develop a robust detection system that minimizes financial risk.

---

### 🎯 Project Objectives
* **Fraud Identification**: Building a predictive model to accurately distinguish between legitimate and fraudulent transactions.
* **Handling Class Imbalance**: Managing a dataset where the minority class (fraud) is significantly underrepresented.
* **Model Benchmarking**: Comparing the performance of different classification algorithms to find the most effective solution.
* **Metric Optimization**: Prioritizing metrics such as Recall and F-Measure to ensure that as many frauds as possible are detected.

---

### 🔬 Methodologies Used
* **Exploratory Data Analysis (EDA)**: Investigating feature distributions such as transaction distance and purchase price ratios.
* **Data Partitioning**: Splitting the dataset into Training (80%) and Test (20%) sets to ensure proper model validation.
* **Classification Modeling**: Training and testing multiple algorithms:
    * **Random Forest** (Identified as the top performer)
    * **Decision Tree**
    * **Logistic Regression**
    * **Naive Bayes**
* **Performance Evaluation**: Comprehensive analysis using Confusion Matrices, ROC Curves, and AUC scores to validate model reliability.

---

### 🛠️ Technologies Used
* **Core Platform**: KNIME Analytics Platform (Workflow-based Machine Learning).
* **Dataset**: Credit Card Fraud dataset (1M samples).
* **Evaluation Metrics**: Accuracy, Precision, Recall, F-Measure, and AUC.
