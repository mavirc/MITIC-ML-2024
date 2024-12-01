
Objetivo

Utilizar técnicas de clasificación aprendidas hasta el momento para predecir la calidad del vino basándose en características físico-químicas. Este ejercicio permitirá aplicar conceptos como la selección de características, preprocesamiento de datos, entrenamiento y evaluación de modelos de clasificación, y análisis de resultados mediante métricas y visualizaciones.

Tecnicas utilizadas:

Modelos de Clasificación:

KNN (K-Nearest Neighbors)
RandomForest (Random Forest)
Regresión Logística (Logistic Regression)
Selección de Hiperparámetros:

Validación Cruzada (Cross-Validation): Utilizada para seleccionar los mejores hiperparámetros de los modelos.

Evaluación de Modelos:

Métricas de Rendimiento:
Exactitud (Accuracy)
Precisión (Precision)
Recall (Recall)
Puntuación F1 (F1-Score)
Matriz de Confusión (Confusion Matrix): Para evaluar la precisión de la clasificación de los modelos.
Informe de Clasificación (Classification Report): Generado para cada modelo, que incluye las métricas de rendimiento.
Curva ROC (Receiver Operating Characteristic Curve) y AUC (Área bajo la Curva ROC): Se visualiza y se calcula para el mejor modelo para evaluar su capacidad de discriminación.


Como ejecitar este notebook
Crear tu entorno virtual (si no deseas trabajar localmente):

Abre tu terminal o consola.
Navega al directorio de tu proyecto.
Crea el entorno virtual usando el siguiente comando
python -m venv nombre_del_entorno

Activa el entorno virtual:
En Windows:
nombre_del_entorno\Scripts\activate

Instalar los paquetes necesarios:

Si tienes un archivo requirements.txt en tu proyecto, puedes instalar todas las dependencias de una vez con:

pip install -r requirements.txt

Ejecutar el notebook