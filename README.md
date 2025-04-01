# Prediccion de Impurezas en Mineria mediante Modelos de Machine Learning 🏭📈
Modelos de regresión lineal para predecir el porciento de impurezas de sílice de un proceso minero.

## Autor ✒️
**Georgina Casillas Rosano**

* [LinkedIn](https://www.linkedin.com/in/georgina-casillas-rosano-data-science)
* [Portafolio]( https://github.com/Georgina-Casillas/Prediccion_Impurezas_en_Mineria_con_Modelos_de_Machine_Learnin)

* Instalación 💻: Este proyecto requiere de instalar Python.

## Objetivos del proyecto: 🎯
* Este trabajo está dedicado al estudio de modelos de regresión lineal aplicados a
un proceso de producción de una industria minera para realizar predicciones del
porciento de impurezas de sílice al final de proceso para facilitar la toma de
decisiones.

* Se espera obtener un modelo de regresión con alta precisión y capacidad de generalización que faciliten el control y optimización del proceso de concentración de hierro.
## Estructura del Proyecto y Metodología 📈

** Las actividades realizadas en este proyecto involucran:

** 1. Extracción de los datos: de la página Kaggle se extraen los datos “Quality
Prediction in a Mining Process” (Magalhães, 2017), esta base contiene los
factores operativos como concentraciones de entrada y salida, flujo de aire,
nivel de las columnas de flotación, pH, etc.

** 2. Análisis exploratorio: Identificar correlaciones entre las variables operativas y
las impurezas. Detectar valores atípicos y patrones estacionales o cíclicos.
Evaluar la calidad de los datos.

** 3. Selección del Modelo Los modelos a probar adecuados incluyen:
* 3.1 Modelos de regresión basados en árboles:
* Random Forest (RF).
* Gradient Boosting (GBRT).
* XGBoost o LightGBM (para mejor rendimiento y flexibilidad).

** 4. Evaluación y Métricas
* Métrica principal: Error Absoluto Medio (MAE) para interpretar los errores
en las mismas unidades de la concentración de sílice.
* Métrica secundaria: R² para evaluar qué tan bien el modelo captura la variabilidad.
* Validación con un conjunto de prueba separado para medir la generalización del modelo.

** 5. Beneficios Operativos y Ambientales
*  Eficiencia Operativa: Menos impurezas significa menos reprocesamiento y
menor desperdicio.
* Sostenibilidad: Reducir las impurezas minimiza los desechos, mejorando el
impacto ambiental.
* Empoderamiento: Los ingenieros pueden anticiparse a los problemas y
tomar decisiones basadas en datos.

## Hallazgos Clave 🔎
* Las predicciones del porciento de impurezas de sílice en la extracción de hierro se realizaron mediante técnicas de análisis avanzadas usando modelos de regresión lineal

* El modelo seleccionado es XGB Regressor ya que destaca como el modelo más preciso y explicativo, el cual tiene un rendimiento de R² de 0.9611, lo que significa que 96.11% de la variabilidad es explicada, una capacidad de ajuste excelente. Con un intervalo de confianza estimado basado en MAE de ± 0.1815%.

* Los beneficios Operativos y Ambientales de realizar estas predicciones incluyen menor reprocesamiento y desperdicio. Reducción de desechos lo cual disminuye el impacto ambiental. Este modelo permitirá a los ingenieros anticiparse a problemas y tomar decisiones basadas en datos.
