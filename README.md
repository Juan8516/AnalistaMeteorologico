# Análisis de Datos Meteorológicos

Este proyecto consiste en analizar un conjunto de datos meteorológicos utilizando Python y NumPy. 
El objetivo es aplicar las técnicas de manipulación de arrays, tratamiento de datos faltantes, 
y análisis estadístico básico en un conjunto de datos del mundo real.

## Acciones realizadas:
1. Se crea un DataFrame a partir de los datos del archivo **datos_meteorologicos.csv**.
2. Se realizan observaciones iniciales de los datos con Pandas.
3. Se convierten las columnas del DataFrame en arrays de NumPy.
4. Identificar los datos faltantes en los arrays, y reemplazarlos por el promedio de los valores del respectivo array.
5. Realizar análisis estadísticos básicos. Mínimamente se espera que puedas extraer la siguiente información de tus arrays:
    * La temperatura promedio
    * El total de precipitaciones
    * La máxima humedad registrada
    * La fecha más calurosa
    * La fehca más fría
6. Exportar los resultados a un nuevo archivo CSV.
