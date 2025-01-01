# 🌳 Algerian Forest Fires Prediction 🔥

This repository contains code for analyzing and predicting forest fires in Algeria using Python. The project involves two main phases:

1. 📊 **Data Cleaning and Preprocessing** - Cleaning and preparing the dataset for modeling.
2. 🌐 **Model Training and Evaluation** - Building and evaluating machine learning models for prediction.

---

## 📃 Dataset
The dataset used in this project contains information about Algerian forest fires, including environmental parameters like temperature, humidity, and wind speed. It is preprocessed to remove missing values and standardize features.

---

## 📁 File Structure

### 1. **cleaning.ipynb** - 🔄 Handles data cleaning and preprocessing.
- Loads the dataset.
- Handles missing values and data types.
- Normalizes and encodes categorical data.
- Generates visualizations for data insights.

### 2. **Model_Training.ipynb** - 🔢 Contains code for building and evaluating machine learning models.
- Splits data into training and testing sets.
- Performs feature scaling.
- Trains models like Linear Regression, Lasso, Ridge, and ElasticNet.
- Evaluates model performance.

---

## 💻 Requirements

Install the required libraries using:
```bash
pip install -r requirements.txt
```

**Key Libraries:**
- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🛠️ Workflow

### 🔄 Data Cleaning
- Load data and remove missing values.
- Normalize numerical features and encode categorical variables.
- Save the cleaned dataset for modeling.

### 👨‍💼 Model Training
- Split data into training and testing sets.
- Apply scaling and correlation-based feature selection.
- Train machine learning models.
- Evaluate models using performance metrics.

---

## 🎯 Results
- 📊 Data cleaning and visualization highlight patterns like fire occurrence trends in August and September.
- 💻 Machine learning models are trained and optimized using techniques like Lasso and Ridge regression.

---

## 📊 Visualizations
- 💡 Distribution plots and correlation heatmaps for exploratory data analysis.
- 💡 Scatter plots and residual plots for model evaluation.

---

## 🛠️ Usage
1. Run the **cleaning.ipynb** notebook to preprocess the data.
2. Execute the **Model_Training.ipynb** notebook to train and evaluate models.

---

## 🌍 Future Work
- Improve model accuracy by experimenting with advanced algorithms like Random Forest or XGBoost.
- Deploy the model as a web application.

---

## 👤 Author
Developed by Uttam Kumar.


