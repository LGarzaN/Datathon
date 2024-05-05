# Equipo Palomas
1. Juan Pablo Chavez A01721844
2. .
3. .
4. .

# Análisis de Tweets con Machine Learning

Este repositorio contiene un script de Python para el análisis y clasificación de tweets en categorías predefinidas utilizando procesamiento de lenguaje natural y machine learning.

## Descripción

El script `analyze_tweets.py` automatiza la clasificación de tweets en español en diversas categorías basadas en su contenido. Utiliza un modelo de lenguaje de spaCy para el preprocesamiento de los textos, vectorización TF-IDF para la transformación de los datos, y un clasificador de Máquina de Soporte Vectorial (SVM) para la predicción de categorías.

## Requisitos

Antes de ejecutar el script, asegúrate de tener instalado Python y las siguientes bibliotecas:

- pandas
- scikit-learn
- spaCy
- NumPy
- SciPy
- nlpaug

Para instalar spaCy y descargar el modelo de lenguaje español, ejecuta:
```bash
pip install spacy
python -m spacy download es_core_news_sm
```
Para instalar las demás dependencias, puedes usar:
```bash
pip install pandas scikit-learn numpy scipy nlpaug
```


