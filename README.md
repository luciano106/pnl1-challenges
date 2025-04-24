# 🧠 Desafíos de Procesamiento del Lenguaje Natural (PNL1)

![Estado](https://img.shields.io/badge/Estado-Completado-00b894)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Disponible-orange)
![Licencia](https://img.shields.io/badge/Licencia-MIT-blue)

Este repositorio agrupa los trabajos prácticos desarrollados como parte del curso **Procesamiento del Lenguaje Natural (PNL1)**. Cada notebook aborda una técnica distinta del PLN, desde modelos estadísticos hasta enfoques neuronales y bots conversacionales.

---

## 🔍 Desafíos Realizados

---

### 1️⃣ Clasificación de textos con Naïve Bayes

![Naive Bayes](https://github.com/luciano106/pnl1-challenges/blob/master/exercises/NaiveBayesClassifier.png)

**Objetivo:**  
Implementar un modelo de clasificación de texto utilizando el algoritmo Naïve Bayes sobre el dataset *20 Newsgroups*.  
Se realizó la vectorización del texto mediante técnicas de bolsa de palabras y TF-IDF, seguida de la evaluación del clasificador en tareas de detección de tópicos.

📎 [Abrir en Colab](https://colab.research.google.com/github/luciano106/pnl1-challenges/blob/master/exercises/PNL1_challenge_1.ipynb)

---

### 2️⃣ Word2Vec entrenado con Don Quijote

![Word2Vec](https://github.com/luciano106/pnl1-challenges/blob/master/exercises/word2vec.jpg)

**Objetivo:**  
El objetivo de este trabajo fue crear vectores de palabras utilizando **Word2Vec de Gensim**, entrenados sobre el texto completo de *Don Quijote de la Mancha*.  
Se aplicaron técnicas de preprocesamiento con spaCy para tokenizar y limpiar el corpus, seguido de una exploración del espacio de embeddings en 2D y 3D mediante PCA y t-SNE.  
Se analizaron relaciones semánticas entre términos del universo narrativo de la obra, observando agrupamientos y proximidades contextuales.

📎 [Abrir en Colab](https://colab.research.google.com/github/luciano106/pnl1-challenges/blob/master/exercises/PNL1-challenge-2.ipynb)

---

### 3️⃣ Modelo de Lenguaje basado en Caracteres (RNN)

![Char RNN](https://github.com/luciano106/pnl1-challenges/blob/master/exercises/rnn.gif)

**Objetivo:**  
Implementar un modelo de lenguaje secuencial utilizando redes neuronales recurrentes (SimpleRNN, LSTM o GRU), entrenado a nivel de **caracteres**.  
El modelo fue entrenado para predecir la siguiente secuencia dada una secuencia de entrada, respetando la estructura many-to-many.  
Se utilizó `rmsprop` como optimizador y se evaluó el rendimiento mediante perplejidad.  
Se generaron textos utilizando greedy search, beam search determinístico y estocástico, analizando el impacto de la **temperatura** sobre la diversidad del texto generado.

📎 [Abrir en Colab](https://colab.research.google.com/github/luciano106/pnl1-challenges/blob/master/exercises/PNL1_challenge_3.ipynb)

---

### 4️⃣ Bot conversacional con datos de ConvAI2

![Chatbot](https://github.com/luciano106/pnl1-challenges/blob/master/exercises/chatbot.jpeg)

**Objetivo:**  
Construir un BOT conversacional basado en el dataset **ConvAI2 (Conversational Intelligence Challenge 2)**, orientado a tareas de preguntas y respuestas (QA).  
Este primer prototipo del bot utiliza conversaciones en inglés para aprender patrones de diálogo y brindar respuestas relevantes al usuario, estableciendo las bases para una arquitectura de diálogo más compleja.

📎 [Abrir en Colab](https://colab.research.google.com/github/luciano106/pnl1-challenges/blob/master/exercises/PNL1-challenge-4.ipynb)

---

## 📝 Notas

- Todos los notebooks están diseñados para ejecutarse directamente en Google Colab.
- Asegurate de tener conexión a internet y una cuenta de Google para acceder y guardar una copia (`Archivo > Guardar una copia en Drive`).
- Las imágenes utilizadas son representativas de los temas tratados y sirven como apoyo visual.

---

## 🧑‍💻 Autor

**Nombre:** Luciano Adassus
**Email:** luciano106@gmail.com 
**Institución:** Universidad de Buenos Aires  
**Curso:** Procesamiento del Lenguaje Natural (PNL1) – 2025
