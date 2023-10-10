# DATA ANALYTICS - PROYECTO INDIVIDUAL Nº2

Este proyecto se centra en un dataset que contiene información detallada sobre accidentes de aviones. Nuestro enfoque incluye un análisis exhaustivo que comienza con un análisis exploratorio de datos. A través de este análisis, identificaremos tendencias a lo largo del tiempo, determinaremos los incidentes más significativos, identificaremos las áreas con la mayor incidencia de accidentes y aplicaremos indicadores clave de desempeño (KPIs) para establecer objetivos claros y medibles.

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

# DASHBOARDS

El dashboard se organiza mediante un navegador de páginas que abarca distintas secciones, incluyendo información detallada sobre países, aeronaves, tendencias y operadores. Además, cuenta con un útil globo de herramienta de ayuda visual (tooltip) para enriquecer la experiencia del usuario.

### PAIS

En la primera página, denominada 'País', ofrecemos una variedad de filtros que incluyen el tipo de país, el operador y la marca de la aeronave. En esta página, presentamos un mapa interactivo donde se representan burbujas que reflejan la magnitud de los accidentes en cada país. Destacamos en amarillo a Estados Unidos, que ha registrado un mayor número de accidentes a lo largo de los años.

Además, en esta página, proporcionamos dos indicadores clave de rendimiento (KPI): la tasa de mortalidad y la tasa de supervivencia. El objetivo de la tasa de mortalidad es mantenerse por debajo del 60%, mientras que el de la tasa de supervivencia es mantenerse por encima del 15%. Estos KPI nos ayudan a evaluar la seguridad de la industria aérea y el impacto de los accidentes.

### MARCA AVIONES

En la segunda página, encontramos la sección marcas de aviones. Podemos aplicar filtros por tipo de marca de avión, lo que nos proporciona una tarjeta informativa con el recuento de fallecidos correspondiente. Además, tenemos un gráfico de barras que muestra la cantidad de accidentes por marca de avion con los diferentes tipos de aeronaves.

Junto a este gráfico de barras, se encuentra un gráfico circular que indica si la aeronave es de uso militar o no, por ultimo, tenemos dos indicadores que muestran el porcentaje de tasa de mortalidad y supervivencia, brindando así una visión completa de la situación en función de las marcas de avión y si es militar o no.

### TENDENCIA

En la siguiente página, titulada 'TENDENCIA', encontramos herramientas de filtrado que permiten seleccionar un rango de años desde 1908 hasta 2021, así como la opción de filtrar por países. Además, en la misma página, se presentan dos indicadores de tasa de mortalidad y tasa supervivencia.

Luego, se encuentra un gráfico de línea temporal que ilustra los mayores accidentes aéreos a lo largo de los años. Complementando esta información, se presenta otro gráfico de línea temporal que representa la tasa de mortalidad a lo largo de los años, junto con un KPI (Indicador Clave de Desempeño) que indica si la tasa de mortalidad se encuentra en cumplimiento. Si la tasa está por debajo del objetivo del 60%, el objetivo no se cumple; si está por encima, se considera que se cumple el objetivo de tasa de mortalidad

### OPERADOR/AEROLINEA



