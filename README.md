# Human Activity Recognition using Machine Learning

This project implements a simple machine learning pipeline to classify human activities (walking, sitting, standing, etc.) using smartphone sensor data.

It was developed as a quick independent project during my Master's in AI & Robotics to demonstrate end-to-end ML workflow skills.

## 📊 Dataset

UCI Human Activity Recognition Using Smartphones Dataset
https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

The dataset contains accelerometer and gyroscope readings from a smartphone worn by participants performing daily activities.

## 🧠 Objective

Build a lightweight activity classifier using classical machine learning methods and evaluate performance.

## ⚙️ Tech Stack

* Python
* Jupyter Notebook
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

## 🚀 Workflow

1. Load and preprocess sensor data
2. Feature selection
3. Train ML models:

   * Logistic Regression
   * Random Forest
   * SVM
4. Evaluate accuracy
5. Compare results
6. Export results summary

## 📈 Results

The models successfully classify activities such as:

* Walking
* Sitting
* Standing
* Laying
* Upstairs/Downstairs

Random Forest achieved the best performance among tested models.

## 📂 Project Structure

human_activity_recognition.ipynb → main notebook
features.txt → feature names
har_results_summary.csv → model results

## 🎓 Why I built this

As a Master's student in AI & Robotics, I wanted a fast, self-contained project that demonstrates:

* ML pipeline implementation
* Data preprocessing
* Model comparison
* GitHub documentation
* Reproducible research

## 👩‍💻 Author

Salouni Das
MSc AI & Robotics

