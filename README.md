# Estrategias de Inversión con Machine Learning

Este repositorio contiene la implementación de estrategias de inversión financiera utilizando técnicas de Machine Learning, desarrolladas en Google Colab.

## 📁 Archivos

- `Implementación de estrategias.ipynb`: Comparación entre el portafolio de estrategias tradicionales y una versión con señales basadas en modelos ML.
- `Implementación_de_estrategia Propia.ipynb`: Estrategia propia de inversión activa en el S&P 500 utilizando redes LSTM, Prophet y embeddings estacionales.

## 📊 Metodología

Se utilizan técnicas como:
- LSTM para detección de oportunidades de subida
- Prophet para predicción de tendencias
- Embeddings para patrones estacionales
- Evaluación quinquenal con ROI, Sharpe Ratio y capital final

## 🛠 Requisitos

Este proyecto fue ejecutado en Google Colab. Para correr localmente, puede ser necesario instalar:
```bash
pip install pandas numpy matplotlib backtrader prophet scikit-learn yfinance


Bajar el indice de precios del cpi , que tambien se utilizo como comparativa
