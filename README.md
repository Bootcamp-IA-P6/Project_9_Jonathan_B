# 🎧 Spotify Classifier - Clasificación de Canciones

## 📌 Objetivo
Construir modelos de clasificación para predecir una variable objetivo (género, popularidad, etc.) usando características de audio de Spotify.

---

## ⚙️ Modelos Implementados

### 1. Modelo Base
- Logistic Regression
- Métricas:
  - Accuracy ≈ 0.70 - 0.75

---

### 2. Modelos Avanzados
- Random Forest
- Decision Tree
- (Opcional) Gradient Boosting

- Mejores métricas:
  - Accuracy ≈ 0.80 - 0.90
  - F1-score alto

---

## 🧠 Variables más importantes

- danceability
- energy
- loudness
- tempo
- valence

Estas variables capturan el comportamiento musical de cada canción.

---

## 📊 Evaluación

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🔍 Conclusiones

- Modelos de árbol funcionan mejor que modelos lineales
- Variables de audio explican bien las diferencias entre clases
- Existe riesgo de overfitting en modelos complejos

---

## 🚀 Posibles mejoras

- Ajuste de hiperparámetros (GridSearch / RandomSearch)
- Balanceo de clases (SMOTE)
- Feature selection
- Modelos más avanzados (XGBoost, LightGBM)

---

## 🧰 Librerías usadas

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📁 Flujo del proyecto

1. Carga de datos
2. Limpieza y preprocessing
3. Análisis exploratorio
4. Modelado
5. Evaluación
6. Conclusiones

---

## ✨ Autor

Clasificación de canciones usando dataset de Spotify