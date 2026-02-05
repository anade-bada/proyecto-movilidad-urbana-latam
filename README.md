# Análisis de Movilidad Urbana en Latinoamérica

## Descripción del Proyecto
Análisis de datos de movilidad urbana y productividad económica en ciudades latinoamericanas, identificando patrones y oportunidades de mejora en el transporte público.

## Contexto
El objetivo del análisis fue evaluar la relación entre la movilidad urbana, medida a través de indicadores de congestión y tiempos de viaje, y la productividad económica, representada por el PIB per cápita a nivel ciudad. La pregunta central busca entender si mayores niveles de congestión urbana están asociados con menores niveles de productividad económica, información clave para orientar decisiones de inversión en infraestructura de transporte y planeación urbana. Las variables clave incluyeron jams_delay, traffic_index_live, travel_time_per_10kms y city_gdp_capita, ya que permiten conectar fricción operativa diaria con resultados.
Por tanto, en este proyecto:
-Integré y limpié dos datasets (TomTom Traffic Index y OECD Cities) que resultó en un dataset unificado de ciudades latinoamericanas para análisis de inversión en infraestructura usando Python y técnicas de data wrangling.
-Analicé la correlación entre congestión vehicular y productividad económica que resultó en identificar ciudades prioritarias para inversión del Latin American Development Bank usando análisis exploratorio y visualización de datos.
-Logro o impacto: Generé recomendaciones estratégicas para inversión en infraestructura de transporte basadas en análisis cuantitativo de movilidad urbana y PIB per cápita.

## Análisis Realizado
- Limpieza y procesamiento de datos
- Análisis exploratorio de datos (EDA)
- Visualizaciones interactivas
- Identificación de patrones de movilidad

## Conclusiones Principales
- Los resultados muestran que la relación entre congestión y productividad no es lineal. Ciudades con alta actividad económica pueden presentar congestión moderada sin afectar negativamente su PIB per cápita. Sin embargo, niveles extremos y persistentes de congestión, sí se asocian con menores niveles de productividad económica.
- Relación congestión vs productividad 🇦🇷 Buenos Aires (ARG), tiene GDP per cápita: relativamente alto. No hay una señal fuerte de que la congestión esté “ahogando” la economía. México: congestión muy alta, pero PIB per cápita también alto → la economía absorbe el costo. Uruguay: PIB alto + congestión mínima → sistema eficiente.
- Caso crítico: Colombia (Bogotá). PIB per cápita: 11,442 (medio–bajo). Congestión: 1,141 (muy alta). Congestión comparable a México, pero sin el respaldo económico. Mucho tiempo perdido con bajo retorno económico. Colombia muestra la peor relación congestión / productividad del conjunto. Bogotá (Colombia) es la ciudad que: combina alta congestión, con baja productividad relativa, mostrando la correlación negativa más preocupante del conjunto.

## Herramientas Utilizadas
- Python
- Pandas
- Matplotlib/Seaborn/NumPy
- Jupyter Notebook

## Archivos del Proyecto
- `notebook_principal.ipynb` - Análisis completo
- `datos_movilidad.csv` - Dataset utilizado
- `graficos/` - Visualizaciones generadas
