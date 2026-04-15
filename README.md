📱 Machine Learning Models for Mobile Price Classification

This repository contains implementations of multiple machine learning algorithms to classify mobile phone prices into different categories based on their specifications.

The project demonstrates how different models perform on the same dataset and compares their effectiveness.

🚀 Project Overview

The goal of this project is to predict the price range of mobile phones using various features such as RAM, battery power, screen size, etc.

We implemented and compared the following models:

Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Support Vector Machine (SVM)
Naive Bayes

All models are implemented using Google Colab notebooks.

📂 Repository Structure
Machine-Learning-Models-for-Mobile-Price-Classification/
│
├── 01_Logistic_Regression.ipynb
├── 02_KNN.ipynb
├── 03_Decision_Tree.ipynb
├── 04_Random_Forest.ipynb
├── 05_SVM.ipynb
├── 06_Naive_Bayes.ipynb
│
├── mobile_price_dataset.csv
└── README.md
📊 Dataset
The dataset is taken from Kaggle
It is a well-known dataset for mobile price classification
Contains features like:
Battery Power
RAM
Mobile Weight
Camera Specs
Screen Dimensions
Connectivity Features

Target variable:

Price Range (0 to 3 categories)
⚙️ Technologies Used
Python
Google Colab
NumPy
Pandas
Matplotlib / Seaborn
Scikit-learn
🧠 Models Implemented
1. Logistic Regression

Basic linear model used for classification.

2. K-Nearest Neighbors (KNN)

Instance-based learning algorithm using distance metrics.

3. Decision Tree

Tree-based model for decision making and classification.

4. Random Forest

Ensemble method using multiple decision trees.

5. Support Vector Machine (SVM)

Effective for high-dimensional data classification.

6. Naive Bayes

Probabilistic classifier based on Bayes' theorem.

📈 Evaluation Metrics

Each model is evaluated using:

Accuracy Score
Confusion Matrix
Classification Report
🎯 Objective
Compare performance of multiple ML models
Understand strengths and weaknesses of each algorithm
Build a solid foundation in classification problems
💡 Key Learnings
Feature importance plays a crucial role in prediction
Ensemble methods (like Random Forest) often perform better
Model selection depends on dataset characteristics
▶️ How to Run
Open any .ipynb file in Google Colab
Upload the dataset if not already available
Run all cells step by step
📌 Future Improvements
Hyperparameter tuning
Cross-validation
Feature engineering
Deploying the model as a web app
