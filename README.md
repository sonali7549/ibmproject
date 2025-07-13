# 💼 Salary Prediction using IBM Watsonx.ai Studio

This project demonstrates how to build a machine learning model to predict salaries based on input features such as education, experience, and job role using **IBM Watsonx.ai Studio**.

## 🚀 Project Overview

Predicting salary accurately is essential for HR analytics, job portals, and workforce planning. This project utilizes IBM’s **Watsonx.ai Studio** to train and deploy a predictive model based on real-world salary data.

## 🧠 Tools & Technologies Used

- **IBM Watsonx.ai Studio**
- **IBM Cloud Object Storage**
- **Python (Pandas, scikit-learn, matplotlib)**
- **Git & GitHub**

## 📁 Dataset

The dataset includes features like:

- `Education Level`
- `Years of Experience`
- `Job Role`
- `Location`
- `Current Salary`

*(Dataset used is either uploaded manually or stored in IBM Cloud Object Storage)*

## 📊 Model Development

Steps followed:

1. **Data Collection** – Uploaded to Cloud Object Storage
2. **Data Preprocessing** – Handling missing values, encoding categorical features
3. **Exploratory Data Analysis (EDA)** – Understanding data distributions
4. **Model Training** – Regression model using scikit-learn
5. **Model Evaluation** – MSE, R² score
6. **Model Deployment** – Deployed in Watsonx.ai

## 📌 Results

- The model achieved an R² score of `XX.X%`
- Ready for deployment to predict salary based on user inputs

## 🛠 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/salary-prediction-watsonx.git
   cd salary-prediction-watsonx

