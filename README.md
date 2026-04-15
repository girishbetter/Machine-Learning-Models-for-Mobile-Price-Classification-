# 📱 Machine Learning Models for Mobile Price Classification

This project focuses on building and comparing multiple machine learning models to classify mobile phone prices into different categories based on their specifications.

The implementation demonstrates how different algorithms behave on the same dataset and highlights their performance differences.

---

## 🚀 Project Overview

The objective of this project is to predict the **price range** of mobile phones using features such as RAM, battery power, camera quality, and other hardware specifications.

The problem is treated as a **multi-class classification task**, where the target variable consists of 4 price categories (0, 1, 2, 3).

---

## 📂 Repository Structure

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

---

## 📊 Dataset Information

- Dataset Source: Kaggle (Mobile Price Classification Dataset)  
- Type: Structured CSV dataset  
- Task: Multi-class classification  

### 🔹 Features Include:
- Battery Power  
- RAM  
- Internal Memory  
- Mobile Weight  
- Camera Specifications (Front & Primary)  
- Screen Width & Height  
- Connectivity (WiFi, Bluetooth, 4G, etc.)  

### 🎯 Target Variable:
- price_range (0 to 3 categories)

---

## ⚙️ Technologies Used

- Python  
- Google Colab  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧠 Models Implemented

The following machine learning models were implemented and evaluated:

1. Logistic Regression  
2. K-Nearest Neighbors (KNN)  
3. Decision Tree  
4. Random Forest  
5. Support Vector Machine (SVM)  
6. Naive Bayes  

---

## 🔬 Implementation Details

Each model was implemented in a separate Google Colab notebook with a consistent workflow:

### 🔹 1. Data Loading
- Dataset was loaded using Pandas  
- Basic inspection using `.head()`, `.info()`, `.describe()`  

### 🔹 2. Data Preprocessing
- Checked for missing values (dataset is mostly clean)  
- Feature and target variables separated  
- No heavy feature engineering required due to clean dataset  

### 🔹 3. Train-Test Split
- Data split into training and testing sets using `train_test_split` (typically 80-20 split)  

### 🔹 4. Feature Scaling
- Applied **StandardScaler** where required (especially for KNN and SVM)  

### 🔹 5. Model Training
- LogisticRegression()  
- KNeighborsClassifier()  
- DecisionTreeClassifier()  
- RandomForestClassifier()  
- SVC()  
- GaussianNB()  

### 🔹 6. Prediction
- Predictions made on test data using `.predict()`  

### 🔹 7. Evaluation
Each model was evaluated using:
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## 📈 Evaluation Metrics

- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-Score  

---

## ▶️ How to Run the Project (Step-by-Step)

### 🔹 Step 1: Clone the Repository
git clone https://github.com/your-username/Machine-Learning-Models-for-Mobile-Price-Classification.git  
cd Machine-Learning-Models-for-Mobile-Price-Classification  

### 🔹 Step 2: Open Google Colab
- Go to: https://colab.research.google.com  
- Click on File → Upload Notebook  

### 🔹 Step 3: Upload Notebook
Upload any one of the following:
- 01_Logistic_Regression.ipynb  
- 02_KNN.ipynb  
- 03_Decision_Tree.ipynb  
- 04_Random_Forest.ipynb  
- 05_SVM.ipynb  
- 06_Naive_Bayes.ipynb  

### 🔹 Step 4: Upload Dataset
- Click on the folder icon (📁) in Colab  
- Upload: mobile_price_dataset.csv  

### 🔹 Step 5: Install Dependencies (if needed)
Run: pip install numpy pandas matplotlib seaborn scikit-learn  

### 🔹 Step 6: Run the Notebook
- Click Runtime → Run All  
- Or run cells step by step  

### 🔹 Step 7: View Results
- Model training output  
- Accuracy score  
- Evaluation metrics  

---

## 💻 Alternative: Run Locally

### 1. Install Python (>= 3.8)

### 2. Install Dependencies  
pip install numpy pandas matplotlib seaborn scikit-learn notebook  

### 3. Start Jupyter Notebook  
jupyter notebook  

### 4. Open any .ipynb file and run all cells  

---

## ⚠️ Important Notes

- Ensure dataset file is in the same directory as the notebook  
- File name should match exactly  
- Update file path inside the notebook if needed  

---

## 🎯 Objective

- Compare multiple machine learning algorithms  
- Understand their performance differences  
- Gain practical experience in classification problems  

---

## 💡 Key Learnings

- Feature scaling significantly affects models like KNN and SVM  
- Ensemble methods like Random Forest often provide better accuracy  
- Different models perform differently on the same dataset  
- Clean datasets reduce preprocessing complexity  

---

## 🔮 Future Improvements

- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)  
- Cross-validation  
- Feature engineering  
- Model deployment (Flask / FastAPI)  
- Adding visualization dashboards  

---

## 📌 Conclusion

This project provides a comparative study of multiple machine learning models applied to a real-world dataset. It highlights how model selection and preprocessing techniques impact overall performance.
