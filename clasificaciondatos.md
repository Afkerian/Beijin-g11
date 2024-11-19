# Clasificación y Estructuración de Datos

**Fecha:** 08/11/2024

[Archivo Excel con datos de clima en Beijing](https://epnecuador-my.sharepoint.com/:x:/g/personal/pablo_pacheco_epn_edu_ec/Eau23rIe74lKjW1gAr-7g6cBCFXIT-ADuTRyI42StOhUYw?e=PYKTmd)

1. **¿Cuáles son los días que presentan una humedad superior a la humedad media de la semana?** 
    - Humedad media de la semana: 75.4%.
    - Días con humedad superior a la media:
        - 21/10/2024
        - 23/10/2024
        - 24/10/2024
        - 25/10/2024
        - 26/10/2024

2. **¿Cuáles son los días  con presión superior a la mediana de la presión de esa semana?** 
    - Mediana de la presión: 30.09 inHg.
    - Días con presión superior a la mediana:
        - 21/10/2024
        - 22/10/2024
        - 23/10/2024
        - 24/10/2024
        - 25/10/2024

3. **¿Cuál de las categorias de la variable Condición es la menos frecuente, en esa semana?** 
    - Categorías y frecuencias:

        - Neblina: 10 veces
        - Lluvia Ligera: 12 veces
        - Nublado: 8 veces
        - Soleado: 7 veces
        - Parcialmente Nublado: 6 veces
        - Despejado: 7 veces
        - Lluvia Moderada: 1 vez

    - Menos frecuente: Lluvia Moderada (1 vez).

4. **¿Cómo se distribuye la velocidad del viento en esa semana?** 
    - Velocidades:

        - Mínima: 0 mph
        - Máxima: 7 mph (promedio general de 3.1 mph).

    - La mayoría de las observaciones están entre 2 y 4 mph.
    - La categoría "Calma" (0 mph) aparece frecuentemente en las noches.


5. **Si se considera las categorias de la variable Viento, ¿cuál categoría   es la más frecuente en esa semana?** 
    - Categorías de dirección del viento y frecuencias:

        - CALMA: 10 veces
        - NE: 8 veces
        - S: 7 veces
        - Otras direcciones: menos de 7 veces.
    - Más frecuente: CALMA (10 veces).

6. **¿Cómo se distribuye la variable Punto de rocío?** 
    - Rango: De 28°F a 54°F.
    - Media: 42.4°F.
    - Mediana: 41°F.
    - Distribución: Moderadamente uniforme, con más valores entre 37°F y 46°F.

7. **¿Cuál de las variables: Temperatura, Presión y Velocidad del viento, presenta menor dispersión?** 
    - Desviaciones estándar:

        - Temperatura: 8.9°F.
        - Presión: 0.07 inHg.
        - Velocidad del Viento: 1.9 mph.
    
    - Menor dispersión: Presión (0.07 inHg).

8. **¿Cuáles son las medidas descriptivas de la variable Humedad? Interprete**  
    - Medidas descriptivas:

        - Mínima: 28%
        - Máxima: 99%
        - Media: 75.4%
        - Mediana: 86%
        - Desviación estándar: 22.3%.
    
    - Interpretación:

        - La humedad varía considerablemente, con valores más bajos en las tardes soleadas (alrededor del 30%) y máximos en las madrugadas (cercanos al 100%).
        - La mediana alta (86%) indica que más de la mitad de las observaciones presentan humedad considerable.


9. **¿Cuáles son las medidas descriptivas de la variable Temperatural? Interprete**  

    - Medidas descriptivas:

        - Mínima: 35°F
        - Máxima: 68°F
        - Media: 53.3°F
        - Mediana: 54°F
        - Desviación estándar: 8.9°F.
    
    - Interpretación:

        - La temperatura fluctúa de manera moderada a lo largo del día. Las mañanas son frías (alrededor de 35-40°F) y las tardes más cálidas (55-68°F).
        - La temperatura es generalmente estable con un rango razonable para la estación.

10. **¿Existe una relación entre la variable Temperatura  y Presión ? ( Consulte el tema:Regresión lineal)** 
    - Relación:
        Se observa una ligera relación inversa entre temperatura y presión: al aumentar la temperatura, la presión tiende a disminuir.

    - Modelo de regresión lineal:
        La ecuación estimada basada en el modelo es:

            Presión = 30.2 − 0.005 × Temperatura 

    - Coeficiente de correlación ($R^2$):

        El $R^2$ es 0.12, indicando que la relación entre estas variables es débil.

    - Conclusión:
        
        Aunque existe una relación inversa, no es lo suficientemente fuerte como para explicar la variación en la presión únicamente mediante la temperatura. Otros factores probablemente afectan significativamente la presión atmosférica.
