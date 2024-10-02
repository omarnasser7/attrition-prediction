# 🌟 Attrition Prediction with LazyPredict 🌟

## 📚 Table of Contents
- [🌟 Attrition Prediction with LazyPredict 🌟](#-attrition-prediction-with-lazypredict-)
  - [📚 Table of Contents](#-table-of-contents)
  - [📚 Overview](#-overview)
  - [🔍 Introduction](#-introduction)
  - [📊 Dataset](#-dataset)
  - [💻 Installation](#-installation)
  - [🔧 Workflow](#-workflow)
    - [🗂️ Data Preprocessing](#️-data-preprocessing)
    - [📈 Model Evaluation with LazyPredict](#-model-evaluation-with-lazypredict)
    - [📊 Visualization of Results](#-visualization-of-results)
    - [🏆 Choosing the Best Model](#-choosing-the-best-model)

## 📚 Overview
This project demonstrates how to use the LazyPredict library to efficiently evaluate multiple classification models for predicting employee attrition. By leveraging LazyPredict, we can quickly compare various models and identify the best-performing one based on relevant metrics.

## 🔍 Introduction
Employee attrition prediction is essential for organizations looking to understand workforce dynamics and implement retention strategies. This notebook uses LazyPredict to automate the training and evaluation of several classification algorithms, making it easier to find the most suitable model for predicting whether employees will leave the organization.

## 📊 Dataset
The dataset used in this project includes employee information with features such as:
- **Employee ID**: Unique identifier for each employee.
- **Attrition**: Indicates whether the employee has left the organization (Yes/No).
- Various demographic and job-related features (e.g., age, job role, salary, tenure).

**Dataset Link**: [Employee Attrition Dataset on Kaggle 🥇](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## 💻 Installation
To run this notebook, you need the following Python libraries:
- `pandas` 📊
- `scikit-learn` 🔍
- `LazyPredict` ⚡
- `matplotlib` 📈
- `seaborn`

## 🔧 Workflow

### 🗂️ Data Preprocessing
The project begins with loading and preprocessing the dataset. Key steps include:
- Handling missing values. ❌
- Feature encoding for categorical variables. 🛠️
- Splitting the data into training and testing sets. 📉📈

### 📈 Model Evaluation with LazyPredict
LazyPredict is employed to evaluate various classification models, streamlining the process of fitting and comparing performance metrics:
- **Accuracy**: The proportion of correct predictions. 📊
- **F1 Score**: A measure of a model's accuracy that considers both precision and recall. 📉
- **Time Taken**: The computational time required for each model. ⏱️

### 📊 Visualization of Results
The notebook includes visualizations to compare model performance, such as:
- Bar plots for Accuracy, F1 Score, and Time Taken. These visualizations help identify models that provide a balance between accuracy and efficiency. 📊✨

### 🏆 Choosing the Best Model
The project concludes with a method to select the best model based on a combination of Accuracy and F1 Score, emphasizing the model that is most effective for predicting employee attrition. 🥇

**Notebook Link**: [Attrition Prediction with LazyPredict on Kaggle 📜](https://www.kaggle.com/code/omarnasser7/attrition-prediction-with-lazy-predict)
