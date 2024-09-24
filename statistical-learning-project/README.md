# 💻 Statistical Learning Project

This project applies various statistical learning methods to analyze the **Heart Diseases Dataset**. The goal is to predict the presence of cardiovascular diseases using different machine learning algorithms, such as logistic regression, decision trees, and random forests.

## 📁 Project Contents

- **project.Rmd**: R Markdown file containing the full analysis, code, and results of the statistical learning models.

## 📊 Summary

### Dataset:
- **Heart Diseases Dataset**: A dataset focused on cardiovascular disease prediction based on various medical and demographic features.

### Goal:
To develop predictive models that can accurately classify individuals as either at risk or not at risk of cardiovascular diseases, using several machine learning techniques.

### 📈 Key Analyses:
- **Data Preprocessing**: Includes data cleaning, handling missing values (using the `mice` package), and feature engineering.
- **Modeling**: The project implements and compares multiple machine learning algorithms, including:
  - **Logistic Regression**
  - **Decision Trees**
  - **Random Forest**
  - **Gradient Boosting Machines (GBM)**
  - **Support Vector Machines (SVM)**
- **Model Evaluation**: ROC curves, accuracy, sensitivity, and specificity are used to evaluate and compare model performance.

## 🛠️ Libraries Used:
- **ggplot2**: For data visualization.
- **caret**: For training and evaluating machine learning models.
- **randomForest**: For implementing random forest models.
- **e1071**: For SVM models.
- **mice**: For handling missing data.
- **ROCR**: For ROC curve analysis.

## 📌 Conclusions:
The project successfully demonstrates the application of various machine learning techniques to predict cardiovascular diseases. While logistic regression provides a baseline, more advanced models like random forests and gradient boosting significantly improve predictive accuracy.


