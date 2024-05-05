# Equipo Palomas
1. Juan Pablo Chavez A01721844
2. Luis Eduardo Garza Naranjo A01721881
3. Ernesto Garza Balderas A01721663
4. Arnau Muro Cors A00832818

# Análisis de Tweets con Machine Learning

Este repositorio contiene 2 scripts de Python para el análisis y clasificación de tweets en categorías predefinidas utilizando procesamiento de lenguaje natural y machine learning y para la clasificación de sentimientos.

## Descripción

El script `sentiment_analysis.ipynb` utiliza un Modelo pre-entrenado de Hugging Face llamado (distilbert-base-multilingual-cased-sentiments-studen)[https://huggingface.co/lxyuan/distilbert-base-multilingual-cased-sentiments-student?] para descifrar el sentimiento detrás del Tweet, y da una probabilidad para las categorías positivo, negativo, y neutral.

El script `MLmodel.ipynb` entrena un modelo SVC lineal para clasificar Tweets en alguna de las siguientes categorías:

- Agradecimiento
- Solicitud de Apoyo
- Comentario Positivo
- Comentario Negativo
- Caso Resuelto
- Comentario Neutral
- Promociones

## Librerias utilizadas

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


