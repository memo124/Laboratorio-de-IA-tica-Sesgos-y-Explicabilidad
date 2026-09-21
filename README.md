# Laboratorio de IA: sesgos y explicabilidad

Entrenamos un Random Forest para predecir la aprobación de préstamos y explicamos sus resultados con SHAP y LIME. Es un ejercicio educativo, no una herramienta para decidir préstamos reales.

## Cómo ejecutarlo

1. Abre este repositorio en VS Code e instala la extensión de Colab.
2. Abre `main.ipynb` y conecta el kernel de Colab desde VS Code.
3. Ejecuta todas las celdas en orden. La primera instala las librerías y otra descarga el CSV; necesitas conexión a internet.
4. Antes de entregar, reinicia el kernel, ejecuta todo y guarda el notebook con sus resultados.

## Contenido

- Preparación de datos y entrenamiento con una división 80/20 y semilla 42.
- Evaluación con Accuracy y F1 para la clase aprobado.
- SHAP global y Waterfall de una solicitud aprobada.
- LIME de una solicitud denegada y reflexión sobre posibles sesgos.

Usamos el dataset [Loan Prediction](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset), disponible como [CSV](https://raw.githubusercontent.com/shrikant-temburwar/Loan-Prediction-Dataset/master/train.csv).

Las explicaciones escritas corresponden a los resultados guardados. Si cambian los datos o las versiones de las librerías, revisa los resultados y actualiza esas interpretaciones.
