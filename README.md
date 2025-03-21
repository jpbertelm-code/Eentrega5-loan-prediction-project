# Proyecto de Predicción de Préstamos

Este proyecto utiliza algoritmos genéticos y una Knowledge Base para seleccionar características y evaluar modelos de clasificación con el objetivo de predecir si un préstamo será aprobado o no.

## Descripción del Proyecto

El conjunto de datos contiene información sobre préstamos, incluyendo características como el género del solicitante, estado civil, ingresos, historial crediticio, entre otros. La variable objetivo es `Loan_Status`, que indica si el préstamo fue aprobado (`Y`) o no (`N`).

El proyecto se divide en las siguientes etapas:
1. **Preprocesamiento de datos**: Imputación de valores faltantes y codificación de variables categóricas.
2. **Selección de características**: Uso de un algoritmo genético para identificar las características más relevantes.
3. **Evaluación de modelos**: Comparación de modelos como `RandomForest`, `XGBoost` y `LogisticRegression` utilizando una Knowledge Base.
4. **Selección del mejor modelo**: Elección del modelo con el mejor F1-score.

## Requisitos

Para ejecutar este proyecto, necesitas tener instalado Python 3.9 o superior. Las librerías requeridas se encuentran en el archivo `requirements.txt`.

### Instalación de Dependencias

Puedes instalar las dependencias ejecutando:

```bash
pip install -r requirements.txt
