# 📊 Proyecto: Análisis Predictivo de Morosidad con Modelos de Machine Learning

Este repositorio presenta un análisis predictivo del riesgo de morosidad crediticia utilizando técnicas de Machine Learning. El objetivo principal es modelar el comportamiento de pago de los clientes de una entidad financiera con base en el dataset `UCI_Credit_Card.csv`.

Se aplican modelos supervisados como **Regresión Logística** y **XGBoost**, evaluando su desempeño con métricas clave para determinar su efectividad en la predicción de clientes morosos.

---

## 🧠 Tecnologías Utilizadas

- R y RStudio
- tidyverse
- caret
- xgboost
- pROC
- corrplot

---

## 🎯 Objetivos del Proyecto

### Objetivo General
Desarrollar un modelo de clasificación que permita predecir la morosidad de clientes a partir de sus características crediticias y comportamentales, utilizando técnicas de aprendizaje supervisado.

### Objetivos Específicos

- Realizar un análisis exploratorio y limpieza del dataset.
- Aplicar preprocesamiento a variables numéricas.
- Entrenar un modelo base con Regresión Logística.
- Entrenar un modelo robusto con XGBoost.
- Comparar métricas de desempeño: Accuracy, Sensibilidad, Especificidad, AUC.
- Elaborar conclusiones con recomendaciones aplicables al negocio.

---

## 🧪 Metodología

1. **Carga y limpieza de datos:** se eliminan columnas irrelevantes y se define la variable objetivo.
2. **Partición de datos:** 80% entrenamiento, 20% prueba.
3. **Preprocesamiento:** escalamiento de variables numéricas.
4. **Modelado:** se entrena Regresión Logística y XGBoost.
5. **Evaluación:** matriz de confusión, curva ROC, métricas comparativas.

---

## 📈 Resultados y Conclusiones

- La **Regresión Logística** obtuvo una alta precisión en la clase no morosa, pero baja capacidad para detectar morosos.
- **XGBoost** mejoró el balance en las métricas y mostró mejor capacidad de detección.
- El análisis confirma que variables relacionadas al historial de pagos son determinantes.
- Se sugiere ajustar umbrales de decisión y aplicar técnicas de balanceo como SMOTE.

---

## 📁 Estructura del Repositorio

```
📦 morosidad-machine-learning
│
├── Proyecto-Análisis-Predictivo-de-Morosidad-con-Modelos-de-Machine-Learning.R              # Script en R con todo el código comentado
├── Proyecto-Análisis-Predictivo-de-Morosidad-con-Modelos-de-Machine-Learning.Rmd            # Archivo RMarkdown editable
├── Proyecto-Análisis-Predictivo-de-Morosidad-con-Modelos-de-Machine-Learningad.html           # Informe final en HTML
├── UCI_Credit_Card.csv               # Dataset fuente (no incluido por tamaño)
└── README.md                         # Este archivo
```

---

## ✍️ Autor

Pedro Yacila - *Estudiante de Ingeniería Estadística e Informática*  
[LinkedIn](https://www.linkedin.com/in/pedro-david-yacila-5a2868264/)

