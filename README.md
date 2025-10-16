# Stock market análisis y predidicción
## Analizar el comportamiento del mercado de valores tecnológicos de EEUU
## Objetivo del proyecto:
  - Uso de **"yfinance"** para cargar datos del mercado de valores.
  - Realizar análisis de riesgo de inversión en base a historial.
  - Predecir precios futuros usando LSTM
---
## Secciones
  1. Cambio histórico del precio de las acciones.
  2. Promedios móviles, para que sirven?.
  3. Rendimiento diario del valor de las acciones en promedio.
  4. Correlación entre acciones de diferentes empresas.
  5. Cuanto arriesgar inviertiendo en una acción en particular
  6. Predecir el precio de cierre usando LSTM
  ---
# RESUMEN
 En el archivo .ipynb correspondiente se puede apreciar la facilidad de carga, exploración, análisis y predicción con LSTM y la comprensión de ciertos conceptos y teoría:

  - **yfinance** facilita la carga de datos bursátiles históricos actualizados a la fecha que permiten evaluar la salud económica de una industria, el comportamiento del mercado, el riesgo y comparar el rendimiento de inversiones.
  - Las librerias de Pandas, Mathplotlib, Seaborne ayudan a entender con claridad ciertos conceptos estadísticos fundamentales para la gestión técnica del mercado bursátil y para explicar con claridad a nuestros clientes el porque de nuestras conclusiones. Por ejemplo como los promedios móviles (MA)nos permiten visualizar el mejor rendimiento de las acciones; o porque el análisis de la media y la desviación estándar determinan el riesgo de una inversión.
  - Por útimo podemos ver a LSTM en acción. Creamos un modelo con la inteligencia y el conocimiento suficiente para predecir el comportamiento en el tiempo del valor de las acciones de una empresa.
    - Cabe mencionar que la teoria de funcionamiento de LSTM y el proceso de la creación y optimización de un modelo (LSTM) han sido explicados extensamente en otros notebooks, de mi propia creación disponibles públicamente en GitHub.
