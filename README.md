# 🏠 Linear Regression on Boston Housing

A Machine Learning project that uses **Linear Regression** to predict house prices using the **Boston Housing dataset**.

## 📌 Project Overview

This project demonstrates how Linear Regression can be used to predict the median value of houses based on different housing-related features.

### 🎯 Objective

The main objective is to:

* Load the Boston Housing dataset
* Perform data preprocessing
* Split the data into training and testing sets
* Build a Linear Regression model
* Train the model
* Predict house prices
* Evaluate model performance

---

## 🛠️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 📊 Dataset

### Boston Housing Dataset

The project uses the **Boston Housing dataset**.

The target variable is:

```text
MEDV
```

which represents the median value of owner-occupied homes.

The dataset contains multiple housing-related features that are used to predict the target value.

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Linear Regression Model
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
```

---

## 🤖 Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict a continuous numerical value.

In this project, the model learns the relationship between the housing features and the house-price target.

### Basic Model

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

y_pred = model.predict(X_test)
```

---

## 📈 Model Evaluation

The model can be evaluated using regression metrics such as:

* Mean Squared Error (MSE)
* R² Score

### Mean Squared Error

MSE measures the average squared difference between actual and predicted values.

### R² Score

R² indicates how well the model explains the variation in the target variable.

---

## 📂 Project Structure

```text
Linear-Regression-Boston-Housing/
│
├── Linear_Regression_on_Bostonhousing.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Linear-Regression-Boston-Housing.git
```

### 2. Open the project

```bash
cd Linear-Regression-Boston-Housing
```

### 3. Install the required libraries

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### 4. Run the notebook

```bash
jupyter notebook
```

Then open:

```text
Linear_Regression_on_Bostonhousing.ipynb
```

You can also run the notebook directly using **Google Colab**.

---

## 📦 Requirements

Create a `requirements.txt` file:

```text
numpy
pandas
matplotlib
scikit-learn
jupyter
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## 🎓 Learning Outcomes

By completing this project, you can understand:

* Basics of supervised learning
* Linear Regression
* Dataset preprocessing
* Feature and target selection
* Train-test splitting
* Model training
* House-price prediction
* Regression model evaluation
* MSE and R² metrics

---

## 👨‍💻 Author

**Mahadev Prasad L**

🎓 Artificial Intelligence & Data Science
🏫 Maharaja Institute of Technology Thandavapura
📚 3rd Year – 5th Semester
🎓 VTU Student

---

## ⭐ Project

This project is created for **academic and learning purposes** as part of Machine Learning studies.

If you find this project useful, please ⭐ star the repository.
