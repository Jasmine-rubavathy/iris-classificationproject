# 🌸 Iris Classification Project

## 📌 Project Overview

This project is a Machine Learning classification model that predicts the species of an iris flower using its physical features.

## 🎯 Goal

To build and compare different classification models to accurately predict iris species based on:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## 📊 Dataset

The dataset used is the famous Iris dataset containing 150 samples with 3 species:

* Setosa
* Versicolor
* Virginica

## 🔍 Exploratory Data Analysis (EDA)

* Checked dataset structure and summary statistics
* Visualized feature distribution using histograms
* Used scatter plots to analyze class separability

## 🤖 Models Used

* k-Nearest Neighbors (k-NN)
* Logistic Regression
* Decision Tree

## 📈 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Precision & Recall

## 🏆 Results

The best-performing model achieved high accuracy in predicting iris species.

## 💾 Model Saving

The final model is saved using joblib as:
iris_model.pkl

## 🔮 Example Prediction

```python
import joblib

model = joblib.load("iris_model.pkl")
sample = [[5.1, 3.5, 1.4, 0.2]]
prediction = model.predict(sample)

print("Predicted species:", prediction)

## 🚀 How to Run

1. Upload dataset (IRIS.csv or iris.xlsx)
2. Open iris.ipynb in Google Colab or Jupyter Notebook
3. Run all cells step by step
4. Train models and evaluate performance

## 📁 Project Files

* iris.ipynb → Main notebook
* iris_model.pkl → Saved model
* IRIS.csv / iris.xlsx → Dataset
* README.md → Project documentation

## ✅ Conclusion

This project demonstrates how machine learning algorithms can be used to classify data effectively and compare model performance.
