# Plagio-CHAT-GPT
Este repositorio pretende reconocer plagio de textos extraídos de CHAT-GPT. No promete funcionar en su totalidad.

Para la detección del plagio se siguió la siguiente metodología:

1. Se recopilaron un conjunto de textos originales de ChatGPT y otro conjunto de textos sospechosos de ser plagio.

2. Se preprocesaron los textos para eliminar las palabras vacías, puntuaciones y caracteres especiales.

3. Se creó una matriz de términos de documentos (DTM) a partir de los textos procesados. Esto implica contar la frecuencia de cada palabra en cada texto y representar los datos en una matriz.

4. Se dividieron los datos en conjuntos de entrenamiento y prueba.

5. Se entrenó un modelo de clasificación, como un clasificador binario o un clasificador de varias clases, utilizando el conjunto de entrenamiento. Se pueden usar diferentes algoritmos de aprendizaje automático, como SVM, Naive Bayes, Redes Neuronales, etc.

6. Se evaluó el modelo utilizando el conjunto de prueba y medir la precisión, la sensibilidad y la especificidad.

Una vez que el modelo esté entrenado, se puede usar para identificar plagio de ChatGPT en textos nuevos.

Nota: Si un texto es etiquetado como plagio, se puede realizar una inspección manual para confirmar el plagio.
