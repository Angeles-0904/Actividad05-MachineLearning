# Actividad 05 - Machine Learning

## Descripción

Este repositorio contiene el desarrollo de la **Actividad 05** del curso de Machine Learning.

## Integrantes

- QUISPE QUISPE SHAMELY ANGELES



# PARTE 3
# Sistema Inteligente de Recomendación de Noticias del Perú utilizando NMF y Similitud del Coseno

## Descripción

Este proyecto implementa un sistema de recomendación de noticias del Perú mediante técnicas de Procesamiento de Lenguaje Natural (NLP). El sistema identifica temas presentes en las noticias utilizando **Non-negative Matrix Factorization (NMF)** y recomienda artículos similares mediante la **Similitud del Coseno**.

## Dataset

El dataset contiene noticias reales recopiladas de medios digitales peruanos mediante RSS.

**Columnas del dataset:**

- titulo
- contenido
- fecha
- fuente
- url

## Metodología

- Carga del dataset.
- Limpieza y preprocesamiento del texto.
- Vectorización mediante TF-IDF.
- Modelado de temas utilizando NMF.
- Cálculo de la similitud del coseno.
- Recomendación automática de noticias similares.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Archivos

- Sistema_Recomendacion_Noticias_Peru.ipynb
- peru_news_dataset.csv
