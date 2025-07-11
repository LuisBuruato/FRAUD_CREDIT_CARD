# 📊 Credit Card Fraud Detection

Este proyecto analiza transacciones de tarjetas de crédito para detectar fraudes utilizando técnicas de análisis exploratorio y modelos de Machine Learning. A continuación se presentan visualizaciones clave generadas durante el análisis.

---

## 1. Distribución de Clases

<p align="center">
  <img src="images/class_distribution.png" alt="Class Distribution" width="600"/>
</p>

> Muestra el desbalance en las clases: 0 = No fraude, 1 = Fraude.

---

## 2. Densidad de Tiempo

<p align="center">
  <img src="images/time_density.png" alt="Time Density" width="600"/>
</p>

> Distribución de tiempo de las transacciones para clases fraudulentas y no fraudulentas.

---

## 3. Monto Total por Hora

<p align="center">
  <img src="images/total_amount.png" alt="Total Amount per Hour" width="600"/>
</p>

> Línea de tiempo del monto total de transacciones por hora, separadas por clase.

---

## 4. Monto Máximo por Hora

<p align="center">
  <img src="images/max_amount.png" alt="Maximum Amount" width="600"/>
</p>

> Gráfico de línea que representa el monto máximo de transacciones por hora.

---

## 5. Diagrama de Caja (Boxplot) del Monto

<p align="center">
  <img src="images/boxplot_amount.png" alt="Boxplot Amount" width="600"/>
</p>

> Boxplot de los montos de transacciones por clase, con y sin outliers.

---

## 6. Monto de Transacciones Fraudulentas

<p align="center">
  <img src="images/fraud_amount.png" alt="Fraud Scatter" width="600"/>
</p>

> Gráfico de dispersión del monto de las transacciones fraudulentas a lo largo del tiempo.

---

## 7. Mapa de Calor de Correlaciones

<p align="center">
  <img src="images/correlation_heatmap.png" alt="Correlation Heatmap" width="600"/>
</p>

> Matriz de correlación de todas las variables del dataset.

---

## 8. lmplot: V20 vs Amount

<p align="center">
  <img src="images/lmplot_v20_amount.png" alt="lmplot V20 vs Amount" width="600"/>
</p>

> Relación entre la variable V20 y el monto, diferenciada por clase.

---

## 9. lmplot: V7 vs Amount

<p align="center">
  <img src="images/lmplot_v7_amount.png" alt="lmplot V7 vs Amount" width="600"/>
</p>

> Relación entre la variable V7 y el monto, diferenciada por clase.

---

## 10. Distribución KDE de todas las variables

<p align="center">
  <img src="images/kde_features.png" alt="KDE Features" width="600"/>
</p>

> Distribuciones Kernel Density Estimation para todas las variables según clase.

---

## 11. Importancia de las Variables (Modelo)

<p align="center">
  <img src="images/feature_importance.png" alt="Feature Importance" width="600"/>
</p>

> Importancia de las características utilizadas por el modelo (por ejemplo, XGBoost).

---

## 12. Matriz de Confusión

<p align="center">
  <img src="images/confusion_matrix.png" alt="Confusion Matrix" width="600"/>
</p>

> Matriz de confusión para evaluar el rendimiento del modelo de clasificación.

---

## 📁 Carpeta `images/`

Todos los gráficos están almacenados en la carpeta [`images/`](https://github.com/LuisBuruato/FRAUD_CREDIT_CARD/tree/main/images).

---

## 🚀 Autor

**Luis Buruato**  
📧 luisburuato@gmail.com  
🔗 [GitHub](https://github.com/LuisBuruato)
