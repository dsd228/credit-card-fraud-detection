---
layout: home
title: Detección de Fraude Financiero
---

<div align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License">
  <h1>🚨 Credit Card Fraud Detection 🚨</h1>
  <h3>Machine Learning · Data Science · Portfolio Profesional</h3>
</div>

---

## 👨‍💻 Sobre el Autor
**David Sebastián Díaz**<br>
Ciencia de Datos · UX Design · Business Intelligence<br>
[Email](mailto:david.diaz.uxdata@gmail.com) | [LinkedIn](https://linkedin.com/in/david-sebastian-diaz-586568332) | [GitHub](https://github.com/dsd228)

---

## 💡 Objetivo
Desarrollar un modelo de machine learning que detecte transacciones fraudulentas de manera precisa y exhaustiva.

- Modelo principal: **Random Forest**
- Manejo de desbalance: **SMOTE**
- Métricas: Precisión, Recall, F1, ROC-AUC
- Interpretabilidad: Importancia de variables

---

## 📁 Estructura del Proyecto
```text
credit-card-fraud-detection/
├── data/
│   └── creditcard.csv
├── notebooks/
│   └── fraud_detection.ipynb
├── images/
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
├── README.md
├── index.md
├── _config.yml
└── LICENSE
```

---

## 📊 Visualizaciones
<div align="center">
  <img src="images/correlation_heatmap.png" alt="Correlation Heatmap" width="350"/>
  <img src="images/confusion_matrix.png" alt="Confusion Matrix" width="350"/>
  <img src="images/roc_curve.png" alt="ROC Curve" width="350"/>
  <img src="images/feature_importance.png" alt="Feature Importance" width="350"/>
</div>

---

## 📈 Métricas Clave
| Métrica       | Valor   |
|---------------|---------|
| Accuracy      | 99.2%   |
| Precision     | 90.5%   |
| Recall        | 87.3%   |
| F1-Score      | 88.9%   |
| ROC AUC       | 98.6%   |

**Enfoque en Recall para minimizar el fraude no detectado.**

---

## 📦 Dataset
- Origen: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transacciones totales, 492 casos de fraude
- Variables: `V1` a `V28` (PCA), `Time`, `Amount`, `Class`

---

## 🚀 Próximos Pasos
- Comparativa con XGBoost y LightGBM
- Interpretabilidad con SHAP
- Demo interactiva con Streamlit
- Análisis de impacto en costos y tasas reales de fraude

---

## 📬 Contacto
¿Tienes dudas o propuestas? ¡Conversemos!
- Email: david.diaz.uxdata@gmail.com
- LinkedIn: [David Sebastián Díaz](https://linkedin.com/in/david-sebastian-diaz-586568332)
- Portafolio: [GitHub](https://github.com/dsd228)

---

## 📄 Licencia
Este proyecto está bajo licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
---
