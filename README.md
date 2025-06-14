 **"NDVI Time-Series Classification - Summer Analytics Hackathon"**:

---

## 🌱 NDVI Time-Series Classification

### Summer Analytics First Hackathon - GeeksforGeeks x IITG

###  Objective

This notebook addresses the **land cover classification task** using **NDVI (Normalized Difference Vegetation Index) time-series data**. The goal is to predict the **land cover type** for each observation using machine learning techniques, particularly focusing on **logistic regression**.

---

###  Problem Statement

Given NDVI values over time for various land areas, classify the land into different categories such as cropland, forest, grassland, etc.

---

###  Dataset

* **Training File**: `hacktrain.csv`
* **Test File**: `hacktest.csv`
* Format: CSV with features representing NDVI values across time points.

---

### 🛠️ Workflow

1. **Exploratory Data Analysis**

   * Basic inspection of shape, data types, and missing values.
   * Distribution of classes (target variable).

2. **Data Preprocessing**

   * Label encoding of the target column (`class`).
   * Normalization or standardization (if applicable).

3. **Modeling**

   * **Logistic Regression** using `sklearn`.
   * Train-test split on training data for local validation.
   * Model training and prediction on test data.

4. **Evaluation**

   * Accuracy, classification report on the validation set.
   * Sample predictions printed.

---

### 🧪 Tools & Libraries

* `numpy`, `pandas` – data handling
* `matplotlib`, `seaborn` – visualizations
* `sklearn` – preprocessing, model building, evaluation

---

### 📈 Results

* Model: Logistic Regression
* Accuracy: *Reported as observed on the validation set*

---

### 📤 Submission

* Generates CSV file with predictions for submission to the hackathon leaderboard.

---


Notebook Link: [Public Kaggle Notebook](https://www.kaggle.com/code/veerankidevisaisri/notebook318e74244a)


