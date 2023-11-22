# Prueba python
Clone este repositorio y siga las instrucciones para su correcta ejecución, dentro encontrará cuatro archivos los cuales son:
1. HistoricoPeajesColombia.csv - Este archivo csv es el que se analizará
2. mpio.json - Este archivo contiene la data para pintar en un mapa de Colombia los departamentos
3. primera_fase.ipynb - Este archivo es la primera parte de la prueba (API)
4. segunda_fase.ipynb - Este archivo es la segunda parte de la prueba (Análisis de datos)
   
## Índice

1. [Prueba técnica Parte 1 (API)](#parte1)
2. [Prueba técnica Parte 2 (Análisis de datos)](#uso)

## Prueba técnica Parte 1

1. [Contextualización](#contextualización)
2. [Preparación](#preparación)
3. [Ejecución](#ejecución)

#### Contextualización
Se realizó una autenticación simple, con usuarios locales la cuál devuelve un token si los usuarios concuerdan con los almacenados

#### Preparación
Para la correcta visualización y funcionamiento del código se deberán instalar las siguientes librerías:
1. uvicorn - servidor usado para ejecutar FastAPI
2. webbrowser - usado para poder abrir una url especifica en el navegador
3. nest_asyncio - soluciona los problemas de concurrencia
4. FastAPI - constructor de APIS
5. jose - biblioteca para trabajar con JWT
6. typing - usado para esperar la lista de usuarios

#### Ejecución
El código se encuentra en notebooks por lo que se deberá ejecutar cada una de las celdas.

## Prueba técnica Parte 2

1. [Contextualización](#contextualización)
2. [Preparación](#preparación)
3. [Ejecución](#ejecución)

#### Contextualización
Se realizó un análisis detallado del documento peajes donde se dió solución a cada interrogante.

#### Preparación
Para la correcta visualización y funcionamiento del código se deberán instalar las siguientes librerías:
1. pandas - usada para análisis de datos
2. numpy - usada para operaciones númericas
3. matplotlib - usada para ver visualizar los datos en 2D
4. sklearn - usada para aprendizaje automático
5. geopandas - usada para generar el los datos del mapa
6. shapely - usada para tratar los datos geometricos mostrados en el mapa

#### Ejecución
El código se encuentra en notebooks por lo que se deberá ejecutar cada una de las celdas.
