# 🛡️ Detección de Fraude Financiero con Aprendizaje Automático

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 👨‍💻 Sobre Mí
**David Sebastián Díaz**  
Certificado en Ciencia de Datos, UX Design y Business Intelligence por Google  
📫 david.diaz.uxdata@gmail.com | [LinkedIn](https://linkedin.com/in/david-sebastian-diaz-586568332) | [GitHub](https://github.com/228)

Aplico visualización de datos, estrategia y aprendizaje automático para resolver problemas reales en contextos interdisciplinarios.

---

## 💡 Objetivo del Proyecto
Este proyecto aplica aprendizaje automático para detectar transacciones financieras fraudulentas usando un conjunto de datos real de Kaggle.

El objetivo es desarrollar un modelo que identifique el fraude con alta precisión y exhaustividad, minimizando falsos negativos y contribuyendo a la reducción de costos reales.

---

## 🧠 Algoritmo y Estrategia
- ✅ Random Forest Classifier  
- ✅ Desbalance de clases manejado con SMOTE  
- ✅ Evaluación con matriz de confusión, ROC-AUC, precisión, recall, F1-score  
- ✅ Análisis de importancia de variables para interpretabilidad  

---

## 📁 Estructura del Repositorio
```
fraud-detection-ml/
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
└── LICENSE
```

---

## 📊 Visualizaciones
| Visual | Descripción |
|--------|-------------|
| 🧱 **Correlation Heatmap** | Muestra relaciones entre variables |
| 🧮 **Confusion Matrix** | Evaluación visual de la precisión del modelo |
| 📈 **ROC Curve** | Tasa de verdaderos positivos vs. falsos positivos |
| 🌟 **Feature Importance** | Las 10 variables más influyentes |

🖼️ Previsualizaciones:

![Correlation Heatmap](images/correlation_heatmap.png)  
![Confusion Matrix](images/confusion_matrix.png)  
![ROC Curve](images/roc_curve.png)  
![Feature Importance](images/feature_importance.png)

---

## 📈 Métricas Clave
| Métrica       | Valor |
|---------------|-------|
| **Accuracy**  | XX.X% |
| **Precision** | XX.X% |
| **Recall**    | XX.X% |
| **F1-Score**  | XX.X% |
| **ROC AUC**   | XX.X% |

🔍 Enfoque estratégico en **exhaustividad** para minimizar casos de fraude no detectados.

---

## 🔍 Dataset
- Fuente: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Transacciones: 284,807 total — 492 casos de fraude
- Variables: `V1` a `V28` (componentes PCA), `Time`, `Amount`, `Class`

---

## 📬 Contacto
📧 dsd228.dd@gmail.com  
🌐 [LinkedIn](https://linkedin.com/in/david-sebastian-diaz-586568332)  
📁 [Portafolio](https://github.com/228)

---

## 📌 Próximos Pasos
- 🔁 Comparar modelos (Random Forest vs. XGBoost / LightGBM)  
- 📊 Agregar interpretabilidad con SHAP  
- 💻 Desplegar como demo interactivo con Streamlit  
- 💡 Integrar análisis de ahorro de costos basado en tasas reales de fraude

---

## 📄 Licencia
Este proyecto está licenciado bajo la MIT License — ver el archivo [LICENSE](LICENSE) para detalles.

---