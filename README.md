# Proyecto Clasificación

<img width="11520" height="3456" alt="DA-Clasificacion" src="https://github.com/user-attachments/assets/d60d0f98-c731-4a1e-83e6-0f65ad0b433b" />


## 📝 Descripción del Proyecto

Para este proyecto vamos a utilizar un conjunto de datos que podamos abordar como un problema de clasificación. Te dejaremos como recurso el siguiente dataset: [**Airlines Dataset**](https://drive.google.com/file/d/1oKFnhKBtO_-eEYenjplsVJAzbcAOYspq/view), solo como sugerencia en caso de no encontrar un dataset adecuado. ¡Más instamos a la autenticidad de vosotrxs!

El objetivo del proyecto será desarrollar un modelo que haga predicciones basándose en ciertos parámetros con un algoritmo de clasificación, por ejemplo en caso de utilizar el dataset de recurso, el modelo deberá ser capaz de predecir la satisfacción de los clientes y posteriormente productivizar esta solución en una pequeña aplicación.

## 📦 Condiciones de Entrega

- El proyecto es **Grupal**.
- Será necesario entregar:
  - Una aplicación que reciba como entrada los datos de un cliente y devuelva la predicción de clasificación.
  - El repositorio en **GitHub**, con el trabajo ordenado en ramas y mensajes de commit limpios.
  - Un informe técnico del rendimiento del modelo (clasificación y explicación del performance).
  - Una presentación para negocio (**PowerPoint, Canva, Prezi, etc.**) y una presentación técnica del código.
  - Enlace del Trello u otra herramienta organizativa utilizada.
- El **overfitting** debe ser inferior al **5%**.

## 🛠️ Tecnologías a usar

- Scikit-learn
- Pandas
- Streamlit / Dash / Gradio
- Git y GitHub
- Docker

## 🏆 Niveles de Entrega  

### 🟢 **Nivel Esencial:**  
✅ Un modelo de machine learning funcional que utilice un algoritmo de clasificación.

✅ Análisis exploratorio de los datos (**EDA**) con visualizaciones relevantes para clasificación (**matriz de correlación, histogramas, etc.**).

✅ Overfitting inferior al **5%** (diferencia aceptable entre métricas de entrenamiento y validación).

✅ Una solución que productivice el modelo (**Streamlit, Gradio, API, Dash, etc.**).

✅ Informe del rendimiento del modelo con métricas de clasificación (**accuracy, recall, precision, F1 score, curva ROC, matrices de confusión, etc.**) y explicación de su performance (**feature importance, análisis de errores**).

---

### 🟡 **Nivel Medio:**  
✅ Modelo de ML con técnicas de **ensemble** (**Random Forest, Gradient Boosting, XGBoost, etc.**).

✅ Uso de técnicas de **Validación Cruzada** (**K-Fold, Leave-One-Out**).

✅ Optimización del modelo con ajuste de hiperparámetros (**GridSearch, RandomSearch, Bayesian Optimization, Optuna**).

✅ Sistema de **recogida de feedback** para monitorizar la performance del modelo en producción (**métricas en tiempo real**).

✅ Sistema de **recogida de datos nuevos** para futuros reentrenamientos (**pipeline de ingestión de datos**).

---

### 🟠 **Nivel Avanzado:**  
✅ Versión **dockerizada** del programa.

✅ Guardado en **bases de datos** de los datos recogidos por la aplicación (**SQL, MongoDB, etc.**).

✅ **Despliegue** (**AWS, GCP, Azure, Render, Vercel, etc.**).

✅ Inclusión de **test unitarios** (**validación de preprocesamiento, métricas mínimas aceptables, etc.**).

---

### 🔴 **Nivel Experto:**  
✅ **Experimentos o despliegues** con modelos de redes neuronales.

✅ Sistemas de **entrenamiento y despliegue automático (MLOps)** con:
  - 🔹 **A/B Testing** para comparar modelos.
  - 🔹 **Monitoreo de Data Drift** para detectar cambios en la distribución de los datos.
  - 🔹 **Auto-reemplazo de modelos** solo si la nueva versión supera métricas predefinidas.

---

## 🎯 Evaluación

- **Competencia:** Evaluar conjuntos de datos utilizando herramientas de análisis y visualización de datos.
- **Competencia:** Aplicar algoritmos de aprendizaje automático según el problema, identificando y resolviendo problemas clásicos de inteligencia artificial.
