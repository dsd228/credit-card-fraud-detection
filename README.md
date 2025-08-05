# 🔍 Credit Card Fraud Detection

Este proyecto aplica técnicas de Machine Learning para detectar transacciones fraudulentas con tarjetas de crédito, utilizando un dataset real altamente desbalanceado.

---

## 📊 Dataset

- Fuente: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transacciones
- Solo 492 fraudes (0.17%)
- Variables anónimas (V1–V28) + `Time`, `Amount` y la clase (`Class`)

---

## 🧪 Tecnologías utilizadas

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Bootstrap 5 para la web
- GitHub Pages
- Jupyter Notebook
- (Opcional: XGBoost, SMOTE, Streamlit o Gradio)

---

## 📈 Modelos evaluados

| Modelo             | Accuracy | Recall | Precision | F1-score | AUC  |
|--------------------|----------|--------|-----------|----------|------|
| Logistic Regression | 0.979    | 0.63   | 0.85      | 0.72     | 0.95 |
| Random Forest       | 0.999    | 0.89   | 0.93      | 0.91     | 0.98 |
| XGBoost             | 0.999    | 0.92   | 0.91      | 0.915    | 0.99 |

---

## 📊 Resultados visuales

- Distribución de clases (fraude vs no fraude)
- Matriz de confusión
- Curva ROC
- Curva Precision-Recall

---

## 📂 Estructura del repositorio



