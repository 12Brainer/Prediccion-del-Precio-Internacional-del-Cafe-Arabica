# ☕ Predicción de Precios de Café (KC=F)

Este proyecto implementa un flujo completo de **Machine Learning aplicado a series temporales** para predecir el precio de los futuros de café (contrato KC=F).  
Se desarrolla como parte de un proyecto de investigación en el **Instituto Tecnológico de Costa Rica (ITCR)**.

## 📊 Descripción
El objetivo principal es **analizar, modelar y predecir precios futuros de café** usando datos históricos de Yahoo Finance (2020–2025).  
Se emplean técnicas de preprocesamiento, análisis exploratorio y modelos de regresión supervisada.

## ⚙️ Tecnologías utilizadas
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  

## 📂 Dataset
- **Fuente:** [Yahoo Finance – KC=F](https://finance.yahoo.com/quote/KC%3DF/)  
- **Periodo:** 2020–2025  
- **Variables:** OHLCV (Open, High, Low, Close, Volume)  

## 🔎 Flujo de trabajo
1. Extracción de datos desde Yahoo Finance  
2. Limpieza y preprocesamiento (valores nulos, normalización, manejo de outliers)  
3. Análisis exploratorio (estadísticas descriptivas y visualizaciones)  
4. Modelado y entrenamiento:  
   - Random Forest Regressor  
   - Perceptrón Multicapa (MLP)  
5. Evaluación y comparación:  
   - RMSE, MAE, R²  
   - Importancia de variables  
6. Pronóstico de precios futuros  

## 📈 Resultados esperados
- Comparación de desempeño entre Random Forest y MLP  
- Identificación de variables más relevantes para la predicción  
- Pronóstico de precios futuros a corto plazo (30 días)  

## 📑 Referencias
El proyecto se basa en bibliografía científica sobre predicción de commodities con *Machine Learning* y en materiales del curso de **Aprendizaje Automático – TEC**.  

---


