# Análisis en Beijing

## Objetivo de análisis

El objetivo del análisis es estudiar las características climáticas de Beijing, identificar patrones de temperatura, precipitaciones y otros factores meteorológicos relevantes, y comprender su comportamiento estadístico. Esto permitirá predecir tendencias, identificar anomalías y obtener una visión más precisa sobre el comportamiento del clima en esta región. Adicionalmente, el análisis estadístico podría ayudar a observar efectos del cambio climático o variaciones estacionales en Beijing.

## Identificación de las variables de estudio

Para un análisis estadístico completo del clima en Beijing, las siguientes variables podrían ser de interés:

- **Temperatura:** para analizar los cambios y extremos térmicos.

- **Punto de rocío:** para evaluar el nivel de humedad y la comodidad atmosférica.

- **Humedad:** para ver la variación en el contenido de vapor de agua en el aire.

- **Viento:** dirección del viento, para analizar patrones de circulación de aire.

- **Velocidad del viento:** para medir la intensidad del viento y su posible influencia en el confort térmico y dispersión de contaminantes.

- **Ráfaga del viento:** velocidad máxima momentánea del viento, que puede indicar fenómenos extremos.

- **Presión:** para observar cambios asociados con condiciones climáticas.

- **Precipitación:** cantidad de lluvia, para estudiar patrones de lluvias y sequías.

- **Condición:** estado del clima (soleado, nublado, lluvioso, etc.), que permite clasificar los tipos de días.

Estas variables te permitirán hacer un análisis completo de las condiciones climáticas en Beijing y extraer conclusiones valiosas sobre sus características y tendencias.

## Clasificación y Estructuración de Datos

| Días       | Temperatura | Punto de rocío | Humedad | Viento | Velocidad del viento | Ráfaga del viento | Presión  | Precipitación | Condición  |
|------------|-------------|----------------|---------|--------|----------------------|-------------------|----------|---------------|------------|
| 21/10/2024 | 55 °F      | 37 °F         | 50%     | SSE    | 4 mph               | 0 mph            | 30,05 en | 0,0 en       | Nublado    |
| 22/10/2024 | 60 °F      | 32 °F         | 35%     | NNO    | 4 mph               | 0 mph            | 30,09 en | 0,0 en       | Despejado  |
| 23/10/2024 | 66 °F      | 39 °F         | 38%     | SSW    | 7 mph               | 0 mph            | 29,92 en | 0,0 en       | Nublado    |
| 24/10/2024 | 68 °F      | 42 °F         | 38%     | NE     | 2 mph               | 0 mph            | 30,01 en | 0,0 en       | Despejado  |
| 25/10/2024 | 67 °F      | 51 °F         | 58%     | S      | 4 mph               | 0 mph            | 30,09 en | 0,0 en       | Justo      |
| 26/10/2024 | 62 °F      | 52 °F         | 70%     | NE     | 4 mph               | 0 mph            | 30,02 en | 0,0 en       | Justo      |
| 27/10/2024 | 64 °F      | 30 °F         | 28%     | NE     | 7 mph               | 0 mph            | 30,06 en | 0,0 en       | Despejado  |
| 28/10/2024 | 66 °F      | 35 °F         | 31%     | SW     | 7 mph               | 0 mph            | 29,91 en | 0,0 en       | Despejado  |

[Archivo Excel con datos de clima en Beijing](https://epnecuador-my.sharepoint.com/:x:/g/personal/pablo_pacheco_epn_edu_ec/Eau23rIe74lKjW1gAr-7g6cBCFXIT-ADuTRyI42StOhUYw?e=PYKTmd)

1. **¿Cuáles son los días que presentan una humedad superior a la humedad media de la semana?** Los días con una humedad superior al promedio semanal (43.5%) son el 21/10, 25/10 y 26/10.

2. **¿Cuáles son los días  con presión superior a la mediana de la presión de esa semana?** Los días con una presión mayor a la mediana semanal (30.04) son el 21/10, 22/10, 25/10, 26/10 y 27/10.

3. **¿Cuál de las categorias de la variable Condición es la menos frecuente, en esa semana?** La categoría menos frecuente es "Justo," que aparece dos veces en comparación con "Nublado" y "Despejado," que aparecen más veces.

4. **¿Cómo se distribuye la velocidad del viento en esa semana?** La velocidad del viento se distribuye en dos valores: 4 mph, que aparece cinco veces, y 7 mph, que aparece tres veces.

5. **Si se considera las categorias de la variable Viento, ¿cuál categoría   es la más frecuente en esa semana?** La dirección de viento "NE" es la más frecuente, ocurriendo tres veces en la semana.

6. **¿Cómo se distribuye la variable Punto de rocío?** El Punto de Rocío tiene un rango de 30°F a 52°F, mostrando una variabilidad amplia durante la semana.

7. **¿Cuál de las variables: Temperatura, Presión y Velocidad del viento, presenta menor dispersión?** La variable Presión presenta la menor dispersión, indicando una variación mínima en sus valores durante la semana.

8. **¿Cuáles son las medidas descriptivas de la variable Humedad? Interprete**  

    - Mínimo: 28%
    - Máximo: 70%
    - Media: 43.5%
    - Mediana: 38%

    Interpretación: La humedad muestra una variabilidad significativa, con valores bajos en algunos días y picos en otros.

9. **¿Cuáles son las medidas descriptivas de la variable Temperatural? Interprete**  

    - Mínimo: 55°F
    - Máximo: 68°F
    - Media: 63.5°F
    - Mediana: 64°F

    Interpretación: La temperatura es relativamente estable a lo largo de la semana, sin fluctuaciones extremas.

10. **¿Existe una relación entre la variable Temperatura  y Presión ? ( Consulte el tema:Regresión lineal)** Al realizar una regresión lineal entre la Temperatura y la Presión, no se observa una correlación significativa entre ambas variables en esta semana, lo que sugiere que los cambios en la temperatura no están relacionados con variaciones en la presión.


---

<div align="center">
    <a href="README.md">Inicio</a> | 
    <a href="actividad_1.md">Retroceder</a> | 
    <a href="actividad_3.md">Siguiente</a>
</div>