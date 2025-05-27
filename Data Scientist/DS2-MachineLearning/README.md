# 🧠 Clasificación de Riesgo de Alzheimer con Machine Learning

Este proyecto fue desarrollado como parte del curso **Data Science II: Machine Learning para la Ciencia de Datos**. Se aplicaron técnicas de análisis exploratorio y modelado supervisado sobre un conjunto de datos clínicos y de estilo de vida para predecir el riesgo de Alzheimer.

## Dataset

- 📊 Registros: 2149 pacientes
- 🔢 Variables: edad, IMC, MMSE, presión arterial, colesterol, actividad física, calidad de dieta, entre otras.
- 📌 Fuente: Proporcionado por Coderhouse

## Objetivo

- Explorar patrones de riesgo vinculados a Alzheimer.
- Evaluar distintos modelos de clasificación.
- Comparar precisión, recall, F1 y AUC.
- Seleccionar el modelo más robusto para apoyar decisiones médicas.

## Modelos evaluados

- Regresión Logística
- Random Forest
- SVM
- Gradient Boosting

## Resultados

- 🏆 **Modelo ganador:** Gradient Boosting (AUC: 0.79, F1 optimizado con umbral 0.45)
- ✅ Precisión ajustada, buen recall y validación cruzada estable.
- 📈 Visualización con t-SNE para insights multivariados.

📄 [Ver presentación del proyecto](./Informe%20-%20Alzheimer.pptx)

📊 [Ver código y dataset](./Proyecto%20Final%20DS2%20-%20Alzehimer)

## Conclusión

El modelo Gradient Boosting ofreció el mejor equilibrio entre sensibilidad y precisión. Se sugiere recalibración periódica del modelo y su monitoreo continuo en contexto clínico.
