# **Prácticas de Regresión Lineal**
# **Libros leídos** 📚
Este proyecto pretende aplicar un modelo de regresión lineal simple para predecir el número de libros leídos en función de las horas de lectura semanales. El dataset utilizado será de kaggle <a href="https://www.kaggle.com/datasets/trushildhokiya/number-of-books-read-simple-linear-regression">"Libros leídos"</a> y cuenta con 300 filas y 2 columnas siendo "Horas_de_lectura" la variable predictora y "Libros_leídos" la variable predicha.
<div style="text-align: center;">
    <img src="https://cdn-icons-png.flaticon.com/128/3534/3534033.png" alt="Logo" >
</div>

## Objetivo 🛣️
El objetivo es predecir el número de libros leídos en función de las horas de lectura semanales. Se espera que el modelo sea capaz de explicar una parte significativa de la variabilidad en el número de libros leídos y proporcionar predicciones precisas y fiables.

## Metodología 💡
1. **Preprocesamiento de los datos**: Dado que los datos tienen un rango o escala muy parecidos no se les aplicará un proceso de normalización o estandarización.
2. **División de datos**: Se dividirán los datos en conjuntos de entrenamiento y prueba en una proporción de 75:25.
3. **Modelado**: Se utilizará el algoritmo de regresión lineal simple de la librería `sklearn.linear_model`.
4. **Evaluación**: Se evaluará el modelo utilizando las métricas MSE y R2 en el conjunto de prueba, y también se realizará el graficado de los residuos.


# **Predicción del Precio de Cierre Ajustado de NVIDIA** 📊

Este proyecto utiliza técnicas de regresión lineal múltiple para predecir el precio de cierre ajustado de NVIDIA en el mercado bursátil. El dataset utilizado contiene <a href="https://www.kaggle.com/datasets/datazng/nvidia-historical-market-data-2023-2024-for-ml">"Datos del mercado bursátil desde 01-04-2023 al 05-13-2024 de Yahoo Finanzas"</a>, con 353 filas y 9 columnas. Las columnas incluyen la fecha, el precio de apertura, el rango, el volumen, el logaritmo de volumen, porcentaje de rentabilidad, media de 3 días del precio ajustado, cierre ajustado del día anterior y el precio de cierre ajustado.
<div style="text-align: center;">
    <img src="https://cdn-icons-png.flaticon.com/128/16183/16183638.png" alt="Logo">
</div>


## Objetivo 🛣️

El objetivo de este proyecto es desarrollar un modelo de regresión lineal múltiple que pueda predecir el precio de cierre ajustado de NVIDIA con una precisión del 90% o más, utilizando las métricas MSE y R2 como criterio de evaluación.

## Metodología 💡

1. **Preprocesamiento de datos**: Se normalizarán los datos utilizando la función `RobustScaler` de la librería `sklearn.preprocessing`.
2. **División de datos**: Se dividirán los datos en conjuntos de entrenamiento y prueba en una proporción de 75:25.
3. **Modelado**: Se utilizará el algoritmo de regresión lineal múltiple de la librería `sklearn.linear_model`.
4. **Evaluación**: Se evaluará el modelo utilizando la métrica MSE y R2 en el conjunto de prueba.



# **Instrucciones de Uso** 📄

1. Clona este repositorio en tu máquina local.
2. Crea un entorno virtual `pip -m venv env`
3. Activalo `env\Scripts\activate` (Windows) o `source env/bin/activate` (Linux/MacOS)
4. Instala las librerías utilizando el siguiente comando: `pip install -r requirements.txt`
