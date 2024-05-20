Proyecto: Análisis de Criptomonedas

Objetivo
El objetivo es analizar un conjunto de datos que contiene información sobre las principales 50 criptomonedas en el mercado, recopilados diariamente desde el 1 de enero de 2015.

Datos de estudio:
* Fecha: Fecha de observación del precio a las 00:00:00 horas.
* Precio: Precio por fecha y hora.
* Volumen de transacciones: Cantidad de transacciones por día.
* Precio (market_cap): Precio de las criptomonedas en el mercado con relación al USD.
* Nombre de la moneda.
* Fuente: Kaggle - Cryptocurrency Historical Prices
  
Actividades
Exploración de datos:
* Revisar el formato y los datos necesarios para analizar el comportamiento de crecimiento y/o decrecimiento en cierto tiempo.

Carga de datos en Pandas DataFrames:
* Conectar el volumen de datos en comparación del valor o capitalización en dólares para el mercado para analizar su comportamiento proporcional.
  
Preprocesado de datos:
* Identificar valores faltantes o nulos, corregirlos y cambiar el tipo de datos.
* Poner los índices en mayúsculas y organizar los datos por valor ascendente.

Visualización de datos:
* Graficar el precio de las 4 criptomonedas más interesantes para el analista en el año 2015 en una sola figura con varios subplots.
  
Cálculos estadísticos:
* Calcular la media de las criptomonedas para el año 2015 y seleccionar la criptomoneda con la menor desviación estándar entre ellas.
  
Determinación de criptomonedas por encima de la media:
* Identificar qué criptomonedas están por encima de la media calculada.
  
Análisis de los últimos tres meses del año 2015:
* Determinar las criptomonedas que tuvieron un mayor valor en el mercado en los últimos tres meses del año 2015.
  
Identificación de la moneda más volátil:
* Encontrar la moneda que tuvo la mayor cantidad de fluctuaciones en el 2015.
  
Identificación de la moneda más estable:
* Encontrar la moneda que tuvo mayor estabilidad en el 2015.
