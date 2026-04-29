# Análisis de Datos de "How I Met Your Mother" (HIMYM)

Este repositorio contiene un proyecto completo de análisis de datos sobre la serie de televisión "How I Met Your Mother". El proyecto abarca desde el procesamiento de transcripciones de episodios mediante Procesamiento de Lenguaje Natural (NLP) hasta la visualización interactiva de datos.

## 📋 Descripción del Proyecto

El objetivo principal es analizar las emociones de los personajes principales a través de sus diálogos y correlacionar estos datos con información de audiencia, valoraciones de IMDB y localizaciones icónicas de la serie.

### Componentes principales:
1. **Análisis de Emociones:** Clasificación automatizada de sentimientos en los diálogos utilizando modelos de Deep Learning.
2. **Enriquecimiento de Datos:** Integración de datos de episodios, ratings de IMDB y coordenadas geográficas.
3. **Visualización:** Dashboard interactivo en Power BI para explorar los hallazgos.

## 📁 Estructura del Repositorio

- `analisis_emociones.ipynb`: Jupyter Notebook que contiene el proceso de carga de datos y el análisis de sentimientos utilizando la librería `transformers` (Hugging Face).
- `How_I_Met_Your_Mother_2a.pbix`: Archivo de Power BI con las visualizaciones y el reporte final.
- `Files/`: Contiene los datasets procesados listos para su análisis:
    - `himym_dialogues_emotions.csv`: Diálogos con la emoción detectada y su puntuación de confianza.
    - `himym_episodes.csv`: Detalles de cada episodio (director, guionista, fecha, audiencia).
    - `himym_imdb.csv`: Puntuaciones de IMDB y resúmenes de episodios.
    - `himym_locations.csv`: Localizaciones recurrentes con sus coordenadas.
- `Originals files/`: Archivos fuente originales antes del procesamiento encontrados en la plataforma Kaggle.

## 🛠️ Tecnologías Utilizadas

- **Python**: Lenguaje principal para el procesamiento de datos.
- **Pandas**: Manipulación y limpieza de estructuras de datos.
- **Transformers (Hugging Face)**: Modelos pre-entrenados para la clasificación de emociones.
- **Power BI**: Creación de dashboards y visualización de datos geoespaciales y temporales.

## 🚀 Cómo empezar

1. **Análisis de Datos**: Para replicar el análisis de emociones, abre `analisis_emociones.ipynb`. Asegúrate de tener instaladas las dependencias:
    ```bash
    pip install pandas transformers torch tqdm
    ```
2. **Visualización**: Abre el archivo `.pbix` con Power BI Desktop para interactuar con los datos.

<img width="1311" height="732" alt="HIMYM" src="https://github.com/user-attachments/assets/a6e745fb-b379-4b66-8028-1f26290e067b" />

---
*Este proyecto fue desarrollado por Ana y Aliris como parte del Módulo 4 de ADALAB.*
