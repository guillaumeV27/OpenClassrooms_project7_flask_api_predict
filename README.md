# Projet 7 — Implémentation d'un modèle de scoring crédit

## 📋 Présentation du projet

Ce dépôt fait partie du **Projet 7 de la formation Data Scientist en alternance d'OpenClassrooms**.

**« Prêt à dépenser »** est une société financière qui propose des crédits à la consommation à des personnes ayant **peu ou pas d'historique de crédit**.

L'entreprise souhaite mettre en place un outil de **scoring crédit** capable d'estimer le risque associé à une demande de prêt.

---

## 🎯 Objectif

L'objectif est de développer un modèle de Machine Learning permettant :

- d'estimer la probabilité qu'un client rembourse son crédit ;
- d'évaluer le risque de défaut du client ;
- de classifier une demande en **crédit accordé** ou **crédit refusé** ;
- de mettre le modèle à disposition à travers une **API REST**.

---

## 🚀 API de prédiction

Ce dépôt contient le code permettant de **déployer le modèle de scoring sous la forme d'une API développée avec Flask**.

L'API reçoit les informations nécessaires concernant un client et utilise le modèle entraîné afin de retourner une prédiction.

### API déployée

L'API est accessible à l'adresse suivante :

👉 [https://flask-api-predict.onrender.com/](https://flask-api-predict.onrender.com/)

---

## 🛠️ Technologies utilisées

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Git / GitHub
- Render

---

## 📁 Structure du projet

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

## 👨‍💻 Auteur Guillaume Vechambre

Projet réalisé dans le cadre de la formation **Data Scientist**

