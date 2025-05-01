🧠 Breast Cancer Prediction API
Este proyecto es una API desarrollada en FastAPI que predice si un tumor de mama es benigno o maligno usando un modelo de Regresión Logística.
Incluye una automatización de CI/CD con GitHub Actions y despliegue de imagen en DockerHub.

🚀 Tecnologías utilizadas
Python 3

FastAPI

Scikit-Learn

Docker

GitHub Actions



📂 Estructura del proyecto

.
├── data/
│   └── data.csv                  # Dataset de cáncer de mama
├── model/
│   └── logistic_regression_model.pkl  # Modelo entrenado
├── endpoints.py                   # Código de la API FastAPI
├── retraining.py                  # Script de reentrenamiento del modelo
├── Dockerfile                     # Archivo para construir imagen Docker
├── requirements.txt               # Lista de librerías requeridas
└── .github/
    └── workflows/
        └── ci.yml                 # Pipeline CI/CD de GitHub Actions
