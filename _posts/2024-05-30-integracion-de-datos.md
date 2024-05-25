---
layout: post
title: "Integración de Datos y Análisis con Docker Compose"
categories:
  - Proyecto
tags:
  - NoSQL
  - Document-oriented database
  - Graph database
  - Docker
  - API
last_modified_at: 2022-08-22T14:25:52-06:00
---

Este proyecto representa una solución completa para la integración de datos y análisis utilizando contenedores Docker y diversas tecnologías de bases de datos.

## Descripción

El objetivo principal de este proyecto es extraer datos de una base de datos relacional mediante una API, transformarlos en documentos y almacenarlos en una base de datos de documentos MongoDB como un _data lake_. Luego, se realiza un análisis general sobre estos datos en MongoDB. Posteriormente, se filtran y procesan ciertos datos y se transfieren a una base de datos de grafos Neo4j para realizar un análisis más profundo y visualización de relaciones.

## Tecnologías Utilizadas

- **Docker Compose:** Para la gestión de los contenedores y la orquestación del entorno.
- **MongoDB:** Base de datos de documentos utilizada como _data lake_.
- **Neo4j:** Base de datos de grafos para el análisis y visualización de relaciones.
- **API:** Se desarrolla una API para la extracción de datos de la base de datos relacional.
- **Análisis de Datos:** Se realizan análisis tanto en MongoDB como en Neo4j para obtener información útil y valiosa.

## Flujo de Trabajo

1. **Extracción de Datos:** La API extrae datos de la base de datos relacional.
2. **Almacenamiento en MongoDB:** Los datos se transforman en documentos y se almacenan en MongoDB.
3. **Análisis en MongoDB:** Se realiza un análisis general sobre los datos almacenados en MongoDB para obtener información inicial.
4. **Transferencia a Neo4j:** Se filtran ciertos datos y se transfieren a Neo4j para su almacenamiento y análisis de grafos.
5. **Análisis en Neo4j:** Se realiza un análisis más profundo en Neo4j, aprovechando la estructura de grafos para descubrir relaciones complejas entre los datos.
6. **Visualización de Resultados:** Se utilizan herramientas de visualización para representar los resultados del análisis de grafos de Neo4j.

## Resultados

- Se logró una integración fluida entre múltiples tecnologías de bases de datos utilizando Docker Compose, lo que facilita la implementación y escalabilidad del sistema.
- Se pudo extraer, transformar y cargar (ETL) datos desde una base de datos relacional a MongoDB de manera eficiente.
- Los análisis realizados en MongoDB proporcionaron información inicial valiosa sobre los datos almacenados.
- El almacenamiento y análisis de datos en Neo4j permitieron descubrir y visualizar relaciones complejas entre los datos, lo que facilita la identificación de patrones y tendencias.