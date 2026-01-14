# Problema de la Mochila – Formulación QUBO
## Descripción general

Este repositorio contiene un proyecto académico en grupo desarrollado como parte del Máster en Computación Cuántica.
El objetivo del proyecto es modelar el problema de la mochila (Knapsack Problem) mediante una formulación QUBO (Quadratic Unconstrained Binary Optimization), explorando cómo problemas clásicos de optimización combinatoria pueden expresarse en un formato compatible con algoritmos cuánticos.

El trabajo se centra principalmente en la formulación del problema, la definición de la función de coste y la optimización del número de variables.

## Descripción del problema

El problema de la mochila es un problema clásico de optimización combinatoria en el que, dado un conjunto de objetos con un peso y un valor asociados, se busca seleccionar el subconjunto que maximiza el valor total sin superar una capacidad máxima de peso.

En este proyecto, el problema se reformula como un modelo QUBO, permitiendo su resolución mediante técnicas de optimización compatibles con quantum annealing y algoritmos variacionales.

La formulación matemática detallada, así como la definición de restricciones y funciones de coste, se encuentra descrita en los archivos y documentos incluidos en este repositorio.

## Estructura del repositorio

El repositorio incluye:

- Definición del priblema de la mochila y su formulación QUBO (01-Knapsack.ipynb)

- Aplicación del modelo a carteras financieras y optimización de variables (02-optimización_carteras-ipynb)

- Benchmark del modelo utilizando datos reales (03-benchmark.ipynb)

## Mi contribución

Este es un proyecto académico realizado en grupo, en el que las tareas se repartieron entre los distintos integrantes.

Mis principales contribuciones fueron:

- Definición y formulación del problema de la mochila como un modelo QUBO

- Obtención, preparación y análisis de los datos utilizados en el benchmark

- Interpretación y discusión de los resultados obtenidos
