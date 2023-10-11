

![](Henry.png)

# DATA ANALYTICS - PROYECTO INDIVIDUAL Nº2

Este proyecto se centra en un dataset que contiene información detallada sobre accidentes de aviones. Nuestro enfoque incluye un análisis exhaustivo que comienza con un ETL, luego con un análisis exploratorio de datos. A través de este análisis, identificaremos tendencias a lo largo del tiempo, determinaremos los incidentes más significativos, identificaremos las áreas con la mayor incidencia de accidentes y aplicaremos indicadores clave de desempeño (KPIs) para establecer objetivos claros y medibles, Para este proyecto, empleamos Python junto con varias de sus bibliotecas, y además creamos un panel interactivo en Power BI para mejorar la experiencia del usuario

## ETL

En el inicio de nuestro proceso, renombramos las columnas para mayor claridad y coherencia. A continuación, observamos el dataframe para determinar el tipo de dato presenta en cada columna y detectar la presencia de valores faltantes. En los casos necesarios, procedimos a ajustar el tipo de dato de ciertas columnas para adecuarlas a nuestros requerimientos.

Identificamos que los valores faltantes se representaban con un signo de interrogación (?). Para que los valores faltantes no afectaran negativamente nuestro análisis, procedimos a sustituirlos por valores vacíos, asegurando así que los datos fueran consistentes y adecuados para su posterior análisis."

## ANALISIS EXPLORATORIO DE DATOS (EDA)

Para comprender los datos presentados, llevamos a cabo observaciones y análisis relacionados entre sí con el fin de extraer conclusiones. Algunos de los enfoques que empleamos incluyen:

- Medidas descriptivas
- Registros duplicados
- Observación y cálculo de la presencia de valores atípicos (Total Fallecidos y Total Sobrevivientes).
- Graficos que incluyen un análisis de los accidentes más graves, desglosados por Linea temporal, país, tipo de avión, aerolínea y aeronaves con mayor número de víctimas.
- Análisis de KPIs que incluye la tasa de mortalidad, la tasa de fatalidad de la tripulación y la media móvil de accidentes a lo largo de los años.

## DASHBOARDS

El dashboard se organiza mediante un navegador de páginas que abarca distintas secciones, incluyendo información detallada sobre países, aeronaves, tendencias y operadores. Además, cuenta con un útil globo de herramienta de ayuda visual (tooltip) para enriquecer la experiencia del usuario.

### PAIS

En la primera página, denominada 'País', ofrecemos una variedad de filtros que incluyen el tipo de país, el operador y la marca de la aeronave. En esta página, presentamos un mapa interactivo donde se representan burbujas que reflejan la magnitud de los accidentes en cada país. Destacamos en amarillo a Estados Unidos, que ha registrado un mayor número de accidentes a lo largo de los años.

Además, en esta página, proporcionamos dos indicadores clave de rendimiento (KPI): la tasa de mortalidad y la tasa de supervivencia. El objetivo de la tasa de mortalidad es mantenerse por debajo del 60%, mientras que el de la tasa de supervivencia es mantenerse por encima del 15%. Estos KPI nos ayudan a evaluar la seguridad de la industria aérea y el impacto de los accidentes.

### MARCA AVIONES

En la segunda página, encontramos la sección marcas de aviones. Podemos aplicar filtros por tipo de marca de avión, lo que nos proporciona una tarjeta informativa con el recuento de fallecidos correspondiente. Además, tenemos un gráfico de barras que muestra la cantidad de accidentes por marca de avion con los diferentes tipos de aeronaves.

Junto a este gráfico de barras, se encuentra un gráfico circular que indica si la aeronave es de uso militar o no, por ultimo, tenemos dos indicadores que muestran el porcentaje de tasa de mortalidad y supervivencia, brindando así una visión completa de la situación en función de las marcas de avión y si es militar o no.

### TENDENCIA

En la siguiente página, titulada 'TENDENCIA', encontramos herramientas de filtrado que permiten seleccionar un rango de años desde 1908 hasta 2021, así como la opción de filtrar por países. Además, en la misma página, se presentan dos indicadores de tasa de mortalidad y tasa supervivencia.

Luego, encontramos un gráfico de línea temporal que presenta los accidentes aéreos más significativos a lo largo de los años. Este gráfico incluye una función de ayuda visual en forma de globo de información (tooltip). Al desplazarnos sobre la gráfica con el cursor, se despliega información detallada que identifica las marcas de aviones asociadas a los accidentes más relevantes en las coordenadas específicas que tocamos.

Complementando esta información, se presenta una tabla con la variacion interanual de accidentes en porcentaje, incluyendo los accidentes de cada año y con los accidentes del año anterior.

### OPERADOR/AEROLINEA

En la última página, encontramos la sección dedicada a los operadores, donde disponemos de filtros por país y operador/aerolínea para una búsqueda personalizada. Además, se presenta información sobre el total de accidentes, el número acumulado de sobrevivientes y el número de fallecidos.
Justo debajo, una gráfica de barras destaca a los operadores que han experimentado el mayor número de accidentes. En un panel lateral, se muestra el porcentaje correspondiente a la tasa de supervivencia en comparación con la tasa de mortalidad.

Por último, una gráfica de línea temporal se encarga de ilustrar la evolución de las tasas de supervivencia a lo largo del tiempo. Estableciendo un objetivo claro, se busca mantener la tasa de supervivencia por encima del 15%, lo que se refleja en un indicador clave de desempeño (KPI) en esta página.

## CONCLUSIONES

- La tendencia anual de accidentes,Nos indica que desde los años 1908 hasta 1945, se observa una tendencia alcista en la cantidad de accidentes. Posteriormente, esta tendencia se mantuvo estable hasta 1989. Sin embargo, a partir de ese año y hasta 2021, se observa una marcada tendencia a la baja. Este declive constante cumple con nuestro objetivo de mantener los accidentes por debajo de nuestra línea de tendencia, respaldada por la media móvil. 

- El objetivo principal de la tasa de mortalidad es mantenerla por debajo del 60%. No obstante, al analizar la sección 'PAÍS' del dashboard, observamos que este objetivo no se ha cumplido a lo largo de los años. Esto señala la necesidad de aumentar la investigación de accidentes y de implementar mejoras en los protocolos de seguridad de manera significativa.

- La tasa de supervivencia se presenta en la sección "País" del dashboard, con el objetivo de mantenerla por encima del 15%. A lo largo de los años, hemos logrado mantener una tasa de supervivencia del 27.8%, lo que indica un cumplimiento exitoso de nuestro objetivo.

- Estados Unidos destaca por tener el mayor número de accidentes aéreos a lo largo de los años. Sin embargo, es importante notar que su tasa de mortalidad se sitúa en el 60.5%, superando ligeramente el objetivo establecido. No obstante, la diferencia es mínima y sugiere un desempeño muy cercano a la meta.



