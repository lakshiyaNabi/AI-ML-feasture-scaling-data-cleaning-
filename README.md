# 🤖 Customer Churn Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Customer%20Churn-blueviolet?style=for-the-badge&logo=python" alt="Machine Learning">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn" alt="Scikit Learn">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">
</p>

<p align="center">
  <b>Predicting which banking customers are likely to leave using Machine Learning.</b>
</p>

---

## ✨ About The Project

Imagine a bank has thousands of customers.

Some customers may be thinking about leaving, but the bank doesn't know *who* they are.

This project uses *Machine Learning* to analyze customer information and predict whether a customer is likely to:

🟢 *Stay with the bank*
🔴 *Leave the bank*

The prediction is based on factors such as age, credit score, geography, balance, products, activity level and more.

---

## 🎬 Project Workflow

text
             📂 Customer Dataset
                     │
                     ▼
              🔍 Data Analysis
                     │
                     ▼
             🧹 Data Cleaning
                     │
                     ▼
          ⚙️ Feature Preprocessing
                     │
                     ▼
            ✂️ Train / Test Split
                     │
                     ▼
             🤖 Model Training
                     │
                     ▼
             📊 Model Evaluation
                     │
                     ▼
          🔮 Churn Prediction
                     │
             ┌───────┴───────┐
             ▼               ▼
        🟢 Stay          🔴 Churn


---

## 🎯 Project Objectives

<details>
<summary>🔎 Click to explore objectives</summary>

<br>

* Understand customer churn patterns
* Clean and prepare real-world customer data
* Perform exploratory data analysis
* Convert categorical information into numerical data
* Prepare features for machine learning
* Train a classification model
* Evaluate model performance
* Predict customer churn

</details>

---

## 📊 Dataset

The project uses the *Churn Modelling Dataset* containing customer banking information.

### 🔑 Important Features

| Feature            | Description              |
| ------------------ | ------------------------ |
| 💳 CreditScore     | Customer's credit score  |
| 🌍 Geography       | Customer's location      |
| 👤 Gender          | Customer gender          |
| 🎂 Age             | Customer age             |
| ⏳ Tenure           | Years with the bank      |
| 💰 Balance         | Account balance          |
| 📦 NumOfProducts   | Number of bank products  |
| 💳 HasCrCard       | Credit card ownership    |
| ⚡ IsActiveMember   | Active membership status |
| 💵 EstimatedSalary | Estimated annual salary  |
| 🚪 Exited          | Churn status             |

### 🎯 Target Variable

text
Exited = 0  →  🟢 Customer Stayed
Exited = 1  →  🔴 Customer Churned


---

## 🧠 Machine Learning Pipeline

text
📥 Load Dataset
      ↓
🔍 Explore Data
      ↓
🧹 Clean Data
      ↓
✂️ Select Features
      ↓
🔢 Encode Categories
      ↓
📏 Scale Features
      ↓
🧪 Train-Test Split
      ↓
🤖 Train Model
      ↓
📊 Evaluate Model
      ↓
🔮 Make Predictions


---

## 🛠️ Tech Stack

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">

<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white">

<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white">

<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square">

<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square">

<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white">

<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white">

</p>

---

## 📈 Model Evaluation

The classification model is evaluated using:

text
🎯 Accuracy
      │
      ├── How many predictions were correct?
      │
🔎 Precision
      │
      ├── How many predicted churners actually churned?
      │
📌 Recall
      │
      ├── How many actual churners were detected?
      │
⚖️ F1-Score
      │
      └── Balance between Precision & Recall


A *Confusion Matrix* is also used to visualize correct and incorrect predictions.

---

## 📁 Project Structure

text
📦 ML-Task-5
│
├── 📂 Dataset
│   └── 📄 Churn_Modelling.csv
│
├── 📓 ML_Task_5(dc).ipynb
├── 📓 ML_Task_5(fs).ipynb
│
└── 📖 README.md


---

## 🚀 Run The Project

### 1️⃣ Clone the repository

bash
https://github.com/jacklnluvs/ML-Task-5.git


### 2️⃣ Open the project

bash
cd ML-Task-5


### 3️⃣ Install dependencies

bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter


### 4️⃣ Launch Jupyter

bash
jupyter notebook


Then open either:

text
📓 ML_Task_5(dc).ipynb


or

text
📓 ML_Task_5(fs).ipynb


---

## 🎮 Interactive Sections

<details>
<summary>🧹 Data Preprocessing</summary>

<br>

The dataset is cleaned and prepared by:

* Removing unnecessary columns
* Checking missing values
* Encoding categorical variables
* Separating input and output variables
* Splitting the dataset
* Scaling numerical features

</details>

<details>
<summary>📊 Exploratory Data Analysis</summary>

<br>

Visualizations are used to understand relationships between customer characteristics and churn.

Examples include:

* Churn distribution
* Age vs churn
* Geography vs churn
* Balance analysis
* Active membership analysis

</details>

<details>
<summary>🤖 Machine Learning</summary>

<br>

The prepared dataset is given to a classification model.

The model learns patterns from existing customers and uses those patterns to predict churn for new customers.

</details>

<details>
<summary>🔮 Prediction</summary>

<br>

The final model predicts one of two classes:

🟢 0 → Customer stays

🔴 1 → Customer churns

</details>

---

## 💡 Business Impact

Customer churn prediction can help businesses move from:

> ❌ *Reacting after customers leave*

to:

> ✅ *Identifying customers who may leave early*

This can help businesses develop targeted retention strategies such as personalized offers, customer support and engagement campaigns.

---

## 🚀 Future Enhancements

* [ ] Compare multiple ML algorithms
* [ ] Perform hyperparameter tuning
* [ ] Handle class imbalance
* [ ] Improve feature selection
* [ ] Build an interactive dashboard
* [ ] Create a Streamlit application
* [ ] Deploy the model online
* [ ] Add real-time churn prediction

---

## 👩‍💻 Author

### *Lakshiya s s*

🎓 BCA Student
💻 Aspiring Full Stack Developer
🤖 Machine Learning Enthusiast

---

## 🔗 Repository

<p align="center">

<a href="https://github.com/jacklnluvs/ML-Task-5">
<img src="https://img.shields.io/badge/⭐%20View%20Project-GitHub-black?style=for-the-badge&logo=github">
</a>

</p>

---

<p align="center">

### ⭐ If this project helped you, consider giving it a star!

*Made with ❤️ + Python + Machine Learning*

</p>
