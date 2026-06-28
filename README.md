# 🏥 Medical Insurance Cost Prediction

A Machine Learning web application that predicts an individual's medical insurance charges based on personal information such as age, BMI, smoking status, number of children, gender, and region.

The project covers the complete Machine Learning workflow, from data preprocessing and exploratory data analysis (EDA) to model training and deployment using Streamlit.

---

## 📌 Project Overview

This project predicts medical insurance costs using a **Linear Regression** model trained on the popular Medical Insurance dataset.

The application allows users to enter their information through an interactive web interface and instantly receive an estimated insurance cost.

---

## 🚀 Features

- Interactive Streamlit Web Application
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Selection
- Standardization using StandardScaler
- Linear Regression Model
- Model Serialization using Joblib

---

## 📂 Dataset

- **Rows:** 1338
- **Columns:** 7

### Features

- Age
- Gender
- BMI
- Number of Children
- Smoking Status
- Region

### Target

- Medical Insurance Charges

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Joblib

---

## 🤖 Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Feature Selection
6. Standardization
7. Train-Test Split
8. Linear Regression Model Training
9. Model Evaluation
10. Web Application Deployment

---

## 📈 Model Performance

| Metric | Score |
|--------|--------|
| R² Score | **0.804** |
| Adjusted R² Score | **0.799** |

---

## 📁 Project Structure

```
Medical-Insurance-Cost-Prediction/
│
├── app.py
├── medical_insurance_cost_prediction.ipynb
├── insurance.csv
├── insurance_model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/
```

---

## ▶️ Run Locally

Clone the repository

```bash
git clone <repository-url>
```

Move into the project folder

```bash
cd Medical-Insurance-Cost-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📸 Project Screenshots

Project screenshots are available inside the **screenshots** folder.

---

## 👨‍💻 Author

**Ashutosh Aryan**

B.Tech CSE Student

Aspiring Data Analyst & Data Scientist

LinkedIn: *(Add your LinkedIn profile link here)*

GitHub: *(Add your GitHub profile link here)*