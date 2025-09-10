# Machine Learning HIT – Supervised Learning Assignment

## 📌 Project Overview
This repository contains the work for the **Supervised Learning assignment** as part of the HIT Machine Learning course.  
We experimented with different classifiers, feature engineering methods, and hyperparameter tuning, and evaluated the models on a wine dataset.

---

## 📂 Repository Contents
- **Assignment_supervised_learning_flow.ipynb**  
  Main notebook with all parts (EDA, Experiments, Final Model, Evaluation).  
- **wine_train.csv / wine_test.csv**  
  Training and test datasets.  
- **README.md**  
  This file.

---

## ⚙️ Methodology
1. **Part 2 - EDA (Exploratory Data Analysis)**  
   - Visualizations of class distribution, correlations, feature distributions.  

2. **Part 3 – Experiments**  
   - Models: Logistic Regression, Random Forest  
   - Feature Engineering:  
     - Scaling (StandardScaler, MinMaxScaler)  
     - Feature Selection (ANOVA f_classif, Mutual Information)  
   - Hyperparameter Tuning via **GridSearchCV** with **5-fold Cross Validation**  
   - Metric: **Macro-F1**  

3. **Part 4 – Final Model**  
   - Training the best configuration on the full training set.  

4. **Part 5 – Evaluation**  
   - Predictions on test set.  
   - Macro-F1 comparison (CV vs Test).  
   - Classification report + confusion matrix.  
   - Example of first 5 predictions.  

---

## 📊 Results
- **Best Model:** Logist
