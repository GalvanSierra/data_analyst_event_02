# Evento Evaluativo N.º 02 — Exploración y análisis de bases de datos

## Información de la asignatura

**Asignatura:** Análisis de Datos
**Código:** 190304018-1
**Evento evaluativo:** N.º 02
**Tema:** Exploración, análisis exploratorio, preprocesamiento y reducción de dimensionalidad

## Integrantes

1 -
2 -
3 - Galvan Sierra David

---

## 🚀 Instalación

1. Clonar el repositorio

   ```bash
   git clone https://github.com/GalvanSierra/data_analyst_event_02.git
   cd data_analyst_event_02
   ```

2. Crear el entorno virtual

   ```bash
   python -m venv .venv
   ```

3. Activar el entorno virtual

   ```bash
   # Windows
   .venv\Scripts\activate

   # macOS / Linux
   source .venv/bin/activate
   ```

4. Instalar las dependencias

   ```bash
     pip install -r requirements.txt
   ```

# 1. Descripción del proyecto

El presente proyecto tiene como objetivo aplicar los conocimientos adquiridos durante las primeras semanas de la asignatura de **Análisis de Datos** mediante la exploración y análisis de diferentes bases de datos.

El proyecto comprende la exploración inicial de diferentes tipos de datos, la selección de una base de datos para el análisis, la realización de un **Análisis Exploratorio de Datos (EDA)**, la aplicación de técnicas de **preprocesamiento** y, finalmente, la utilización de técnicas de **reducción de dimensionalidad**.

Todo el proceso será documentado en este repositorio de GitHub, manteniendo la trazabilidad de los aportes realizados por cada integrante mediante commits.

## Objetivos

### Objetivo general

Explorar y analizar una base de datos de imágenes mediante técnicas de análisis exploratorio, preprocesamiento y reducción de dimensionalidad, con el propósito de identificar sus principales características y patrones.

### Objetivos específicos

- Explorar diferentes bases de datos y comparar sus características.
- Seleccionar una base de datos de acuerdo con criterios de relevancia, documentación, completitud y manejabilidad.
- Realizar un análisis exploratorio de la base de datos seleccionada.
- Identificar características, distribución y posibles problemas de calidad de los datos.
- Aplicar técnicas de preprocesamiento adecuadas para los datos.
- Aplicar técnicas de reducción de dimensionalidad.
- Analizar e interpretar los resultados obtenidos.

---

# 2. Fase 1: Exploración de bases de datos

## 2.1 Base de datos seleccionada: Fashion-MNIST

Para la exploración de datos de tipo imagen se seleccionó **Fashion-MNIST**, un conjunto de datos diseñado para la clasificación de imágenes de artículos de vestuario.

El conjunto está compuesto por imágenes en escala de grises correspondientes a diferentes categorías de prendas de vestir. Cada imagen tiene una resolución de **28 × 28 píxeles**, por lo que puede representarse numéricamente mediante **784 valores de píxel**.

La base de datos contiene **70.000 imágenes**, distribuidas en 10 categorías diferentes de artículos de vestuario.

### Fuente

**Fuente:** Zalando Research / Fashion-MNIST
**Plataforma consultada:** Kaggle
**Enlace:** https://www.kaggle.com/datasets/zalando-research/fashionmnist

Fashion-MNIST fue desarrollado como un conjunto de datos alternativo a MNIST para evaluar algoritmos de aprendizaje automático utilizando imágenes de artículos de moda.

De acuerdo con su origen, se considera una fuente de datos **secundaria**, debido a que los datos fueron recopilados y organizados previamente por sus creadores para ser utilizados en investigación, experimentación y evaluación de algoritmos.
