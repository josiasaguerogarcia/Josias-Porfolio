# 🏦 Análisis de Préstamos con Incumplimiento (Loan Default)

Este proyecto fue desarrollado durante el curso **Data Science I: Fundamentos para la Ciencia de Datos**. Se realizó un análisis exploratorio y una evaluación de modelos de clasificación sobre un dataset de préstamos, con el objetivo de detectar patrones que permitan predecir el incumplimiento de pagos.

## Dataset

📂 Fuente: [Kaggle - Loan Default Dataset](https://www.kaggle.com/datasets/yasserh/loan-default-dataset)  
📄 Cantidad de registros: 148.670  
📊 Variables: género, ingresos, propósito del préstamo, tasa de interés, duración, monto, entre otros.

## Objetivo

- Identificar variables que influyen en el incumplimiento.
- Evaluar modelos de clasificación (Logistic Regression, Random Forest, Árbol de Decisión).
- Comparar métricas de precisión, recall, F1 y ROC-AUC.
- Generar recomendaciones para mejorar la detección de riesgo crediticio.

## Herramientas utilizadas

- Python (Google Colab)
- Pandas, NumPy
- Seaborn, matplotlib, missingno
- Scikit-learn (modelos + métricas)

## Resultados

- **Regresión Logística**: Accuracy 86.5%, Recall 49%, F1 64%
- **Random Forest**: Accuracy 100% (riesgo de overfitting)
- **Árbol de Decisión**: Accuracy 100%, con una única clasificación errónea

📄 [Ver informe completo en PDF](./Informe%20-%20Prestamos.pdf)


📊 [Ver código en](./Data%20Scientist/DS1-Fundamentos/Notebook%20Proyecto%20Final%20DS1.ipynb)
## Conclusión

Los modelos de árboles superaron a la regresión logística, pero presentan riesgo de sobreajuste. Se recomienda validación cruzada y exploración de modelos adicionales.
