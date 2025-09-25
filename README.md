# Análisis de NLP: Exploración de la Poética y Evolución Temática en las Letras de Shakira

## Descripción

Este proyecto tiene como objetivo analizar las letras de las canciones de Shakira mediante técnicas de Procesamiento del Lenguaje Natural (NLP). El corpus abarca la discografía en español de la artista, desde sus inicios en los años 90 hasta sus producciones más recientes, permitiendo observar la evolución estilística y temática a lo largo del tiempo.

A través del preprocesamiento de texto, análisis de frecuencia, extracción de características léxicas y análisis semántico, se busca identificar patrones de lenguaje, emociones predominantes y características distintivas de cada etapa musical. También se exploran similitudes entre canciones y agrupaciones naturales dentro del corpus.

## Información del Corpus
- **Tipo**: Música
- **Tamaño**: 78 canciones, aproximadamente 35.000 palabras
- **Fuentes principales**: Letras obtenidas manualmente desde fuentes confiables como LyricFind, Wikipedia y sitios oficiales
- **Período temporal**: 1991 – 2024
- **Criterios de selección**: Letras escritas e interpretadas por Shakira en español, organizadas por año y álbum, priorizando variedad temática y temporal

## Técnicas de NLP Aplicadas
- Preprocesamiento de texto (limpieza, tokenización, stop words, lematización)
- Análisis con Bag of Words (BoW) y TF-IDF
- Representación semántica con Word Embeddings (spaCy)
- POS Tagging para análisis gramatical
- Análisis de sentimientos para detección de polaridad emocional
- Extracción de entidades nombradas (NER)

## Principales Hallazgos
- El vocabulario recurrente evidencia una fuerte carga emocional y autorreferencial, con temas como amor, desamor, tiempo, y libertad.
- TF-IDF reveló términos simbólicos y únicos que caracterizan las letras de cada álbum, mientras que BoW resaltó la frecuencia léxica global.
- Los análisis de similitud mostraron coherencia temática dentro de álbumes, y outliers en canciones estilísticamente diferentes.
- Embeddings (spaCy) ofrecieron resultados más intuitivos en comparación con BoW/TF-IDF al capturar similitudes semánticas entre letras.

## Tecnologías Utilizadas
- Python 3.x
- pandas, numpy
- scikit-learn
- spaCy
- matplotlib, seaborn
- nltk, wordcloud
- tqdm, collections, unicodedata, re, glob, os

## Instrucciones de Reproducción
1. Clonar este repositorio
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el notebook: `jupyter notebook notebooks/analisis_integrador.ipynb`

## Limitaciones y Trabajo Futuro
- El modelo no analiza el componente musical ni prosódico de las canciones, que aportan significado adicional.
- El análisis depende de la calidad del texto procesado y no capta metáforas complejas ni ironías.
- Futuras mejoras podrían incluir embeddings contextuales (como BERT), análisis multimodal (texto + audio), y clasificación automática de canciones por emoción o estilo.

## Autor
Carmen Rodríguez - [95697194@ifts24.edu.ar]  
Trabajo Integrador - NLP - Septiembre 2025
