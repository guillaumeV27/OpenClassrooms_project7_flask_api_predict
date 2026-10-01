# Project 7 — Credit Scoring Model Implementation

[🇫🇷 Version française](README_FR.md)

## 📋 Project Overview

This repository is part of **Project 7 of the OpenClassrooms Data Scientist apprenticeship program**.

**"Prêt à dépenser"** is a financial company that provides consumer loans to people with **little or no credit history**.

The company aims to implement a **credit scoring system** capable of assessing the risk associated with a loan application.

---

## 🎯 Objective

The objective is to develop a Machine Learning model that can:

- estimate the probability that a client will repay their loan;
- assess the client's risk of default;
- classify a loan application as **approved** or **rejected**;
- make the model available through a **REST API**.

---

## 🚀 Prediction API

This repository contains the code required to **deploy the credit scoring model as an API developed with Flask**.

The API receives the required client information and uses the trained model to return a prediction.

### Deployed API

The API is available at:

👉 [https://flask-api-predict.onrender.com/](https://flask-api-predict.onrender.com/)

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Git / GitHub
- Render

---

## 📁 Project Structure

```text
.
├── app.py
├── requirements.txt
├── model/
│   └── model.pkl
├── data/
├── README.md
└── ...
```

---

## 👨‍💻 Author

**Guillaume Vechambre**

Project developed as part of the **OpenClassrooms Data Scientist program**.
