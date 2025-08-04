---
layout: default
title: Credit Card Fraud Detection
---

<style>
  body {
    background-color: #0f0f0f;
    color: #f0f0f0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0 20px;
  }

  h1, h2, h3 {
    color: #00ffff;
    animation: glow 2s infinite alternate;
  }

  @keyframes glow {
    from {
      text-shadow: 0 0 10px #00ffff, 0 0 20px #0088ff;
    }
    to {
      text-shadow: 0 0 20px #00ffff, 0 0 40px #0088ff;
    }
  }

  a.button {
    display: inline-block;
    margin: 10px 0;
    padding: 12px 24px;
    background: linear-gradient(90deg, #00ffff, #0088ff);
    color: #0f0f0f;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    transition: all 0.3s ease-in-out;
    box-shadow: 0 0 18px #00ffff44;
    animation: float 2.5s infinite ease-in-out alternate;
  }
  a.button:hover {
    transform: scale(1.05) rotate(-2deg);
    background: linear-gradient(90deg, #0088ff, #00ffff);
    color: #fff;
    box-shadow: 0 0 28px #00ffff99;
  }
  @keyframes float {
    from { transform: translateY(0); }
    to   { transform: translateY(-8px); }
  }

  code {
    background-color: #1f1f1f;
    padding: 2px 4px;
    border-radius: 4px;
    color: #ffcc00;
    animation: codepulse 1s infinite alternate;
  }
  @keyframes codepulse {
    from { box-shadow: 0 0 8px #ffcc00; }
    to   { box-shadow: 0 0 14px #ffcc00; }
  }

  .container {
    max-width: 960px;
    margin: auto;
    padding-top: 40px;
    animation: fadein 2s;
  }
  @keyframes fadein {
    from { opacity: 0; }
    to   { opacity: 1; }
  }

  .metrics {
    display: flex;
    gap: 24px;
    justify-content: center;
    margin: 32px 0;
    flex-wrap: wrap;
  }
  .metric-card {
    background: linear-gradient(90deg, #222, #0f0f0f 80%);
    padding: 18px 28px;
    border-radius: 16px;
    color: #00ffff;
    font-weight: bold;
    box-shadow: 0 0 22px #00ffff44;
    min-width: 120px;
    font-size: 1.2em;
    text-align: center;
    animation: float 2.5s infinite alternate;
  }

  .images-row {
    display: flex;
    gap: 24px;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 18px;
  }
  .images-row img {
    border-radius: 16px;
    box-shadow: 0 0 18px #00ffff55;
    width: 330px;
    max-width: 98vw;
    animation: fadein 2s;
  }

  footer {
    margin-top: 40px;
    text-align: center;
    color: #777;
    font-size: 0.8em;
    animation: fadein 3s;
  }
</style>

<div class="container">
  <h1>🌐 Credit Card Fraud Detection</h1>
  <p>Bienvenido a un proyecto global de detección de fraude financiero usando machine learning e ingeniería de datos.</p>

  <a class="button" href="https://github.com/dsd228/credit-card-fraud-detection" target="_blank">🔗 Ver Repositorio</a>
  <a class="button" href="https://dsd228.github.io/credit-card-fraud-detection/report" target="_blank">📊 Ver Informe</a>

  <h2>🚀 Descripción Futurista</h2>
  <p>Aplicación interdisciplinaria de inteligencia artificial para identificar fraudes en tarjetas de crédito a escala global. Algoritmos avanzados, dashboards interactivos y visualización profesional.</p>

  <h3>⚙️ Tecnologías usadas</h3>
  <ul>
    <li>Python, Scikit-learn, Pandas, NumPy</li>
    <li>Visualización: Matplotlib, Seaborn</li>
    <li>Despliegue: Streamlit, Jupyter</li>
  </ul>

  <h2>📈 Principales Resultados</h2>
  <div class="metrics">
    <div class="metric-card">Accuracy<br><code>99.2%</code></div>
    <div class="metric-card">Precision<br><code>90.5%</code></div>
    <div class="metric-card">Recall<br><code>87.3%</code></div>
    <div class="metric-card">F1-Score<br><code>88.9%</code></div>
    <div class="metric-card">ROC AUC<br><code>98.6%</code></div>
  </div>

  <h2>🖼️ Visualizaciones</h2>
  <div class="images-row">
    <img src="images/correlation_heatmap.png" alt="Correlation Heatmap">
    <img src="images/confusion_matrix.png" alt="Confusion Matrix">
    <img src="images/roc_curve.png" alt="ROC Curve">
    <img src="images/feature_importance.png" alt="Feature Importance">
  </div>

  <h3>📦 Dataset</h3>
  <ul>
    <li>Fuente: <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud" style="color:#00ffff;">Kaggle Credit Card Fraud Detection</a></li>
    <li>284,807 transacciones, 492 fraudes</li>
    <li>Variables: <code>V1-V28</code> (PCA), <code>Time</code>, <code>Amount</code>, <code>Class</code></li>
  </ul>

  <h2>🌟 Próximos Pasos</h2>
  <ul>
    <li>Comparativa con XGBoost y LightGBM</li>
    <li>Interpretabilidad avanzada con SHAP</li>
    <li>Demo interactiva con Streamlit</li>
    <li>Análisis de impacto financiero real</li>
  </ul>

  <h2>🤝 Contacto</h2>
  <ul>
    <li>Email: david.diaz.uxdata@gmail.com</li>
    <li>LinkedIn: <a href="https://linkedin.com/in/david-sebastian-diaz-586568332" style="color:#00ffff;">David Sebastián Díaz</a></li>
    <li>Portafolio: <a href="https://github.com/dsd228" style="color:#00ffff;">GitHub</a></li>
  </ul>

  <footer>
    © 2025 David Díaz – Proyecto portafolio global, ingeniería y UX/UI avanzado
  </footer>
</div>
