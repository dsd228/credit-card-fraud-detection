# credit-card-fraud-detection
Proyecto interdisciplinario de machine learning para detección de transacciones fraudulentas · Portfolio profesional

# 💳 Credit Card Fraud Detection · Portfolio Profesional

Este proyecto forma parte de mi portafolio como Analista Certificado por Google en Ciencia de Datos, Business Intelligence y UX.  
Se aplica machine learning para identificar transacciones fraudulentas, utilizando Random Forest y visualizaciones clave.

---

## 📊 Dataset

- **Fuente:** Kaggle – [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transacciones reales
- 492 etiquetadas como fraudulentas (`Class = 1`)

---

## 🧠 Modelo

- Algoritmo: Random Forest
- División de datos: entrenamiento y validación
- Métricas: matriz de confusión · precisión · recall · curva ROC
- Balanceo de clases (SMOTE opcional)

---

## 📈 Visualizaciones

- Mapa de calor (`heatmap`) de correlaciones
- Matriz de confusión
- Curva ROC

---

## ⚙️ Requisitos

```bash
pip install pandas scikit-learn matplotlib seaborn imbalanced-learn

