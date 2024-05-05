# Análisis de Tweets con Machine Learning

Este repositorio contiene 2 scripts de Python para el análisis y clasificación de tweets en categorías predefinidas utilizando procesamiento de lenguaje natural y machine learning y para la clasificación de sentimientos.

## Descripción

El script `sentiment_analysis.ipynb` utiliza un Modelo pre-entrenado de Hugging Face llamado [distilbert-base-multilingual-cased-sentiments-student](https://huggingface.co/lxyuan/distilbert-base-multilingual-cased-sentiments-student?) para descifrar el sentimiento detrás del Tweet, y da una probabilidad para las categorías positivo, negativo, y neutral. Tambien se puede encontrar en [Google Colab](https://colab.research.google.com/drive/1kb4KKI_zuH_A40VQxeqV3VmbrkWPd7YQ?usp=sharing)

El script `MLmodel.ipynb` entrena un modelo SVC lineal para clasificar Tweets en alguna de las siguientes categorías:

- Agradecimiento
- Solicitud de Apoyo
- Comentario Positivo
- Comentario Negativo
- Caso Resuelto
- Comentario Neutral
- Promociones

Tambien se puede encontrar en [Google Colab](https://colab.research.google.com/drive/1j835dwpmS1lt2ihxUaMa4weTxUDMqT_n?usp=sharing)

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

# Nuestro Equipo
1. Juan Pablo Chavez - jp.chavezm@hotmail.com
2. Luis Eduardo Garza Naranjo - A01721881@gmail.com
3. Ernesto Garza Balderas - A01721663@tec.mx
4. Arnau Muro Cors A00832818@tec.mx
