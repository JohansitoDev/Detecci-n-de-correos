# 🚀 Detección de Spam con Machine Learning (UCI Dataset)

¡Bienvenidos! Este es un proyecto colaborativo de **Inteligencia Artificial** desarrollado en Python. Como equipo de futuros ingenieros, hemos diseñado un modelo de **Aprendizaje Supervisado** para resolver el desafío técnico de clasificar mensajes como **Spam** o **Ham** (correo legítimo).


## 🎯 Objetivo del Proyecto
El objetivo de nuestro grupo fue investigar los fundamentos del Machine Learning y construir un modelo funcional capaz de predecir la categoría de un mensaje basándose en patrones estadísticos y características de contenido.

## 📚 Fase de Investigación (Fundamentos Teóricos)

Durante nuestra investigación, nos enfocamos en entender los pilares que hacen de Python el lenguaje líder en IA:
* **Ecosistema Técnico:** Utilizamos **Pandas** y **NumPy** para la gestión eficiente de grandes volúmenes de datos, y **Scikit-learn** para la implementación del modelo.
* **Tipos de Aprendizaje:** Diferenciamos el aprendizaje supervisado (nuestro caso) del no supervisado y por refuerzo.
* **Algoritmo de Regresión Logística:** Seleccionamos este algoritmo por su eficacia en problemas de **clasificación binaria**, permitiéndonos obtener probabilidades precisas para cada mensaje analizado.

---

## 🛠️ Desarrollo del Trabajo Práctico

### 1. Selección y Carga del Dataset
Elegimos el dataset **Spambase** de la **UCI Machine Learning Repository**. Este conjunto de datos nos proporcionó una base sólida con miles de ejemplos reales etiquetados.

### 2. Análisis Exploratorio de Datos (EDA)
Realizamos una limpieza de datos y generamos visualizaciones clave:
* **Distribución de Clases:** Para asegurar que nuestro modelo no tuviera sesgos hacia una categoría.
* **Análisis de Correlación:** Usamos gráficos para identificar qué palabras (como "money", "free" o "offer") tienen mayor peso en la decisión de la IA.

### 3. Fase de Entrenamiento
Dividimos nuestro conjunto de datos siguiendo el estándar de la industria:
* **80% para Entrenamiento:** Donde el algoritmo "aprendió" a identificar el spam.
* **20% para Prueba (Test):** Donde evaluamos la capacidad de respuesta ante datos nuevos.

### 4. Evaluación y Métricas
Para validar nuestro trabajo, generamos una **Matriz de Confusión**. Esta herramienta nos permitió medir la precisión y entender el comportamiento del modelo ante falsos positivos y falsos negativos.

---

## 💻 Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Plataforma:** Google Colab
* **Librerías Principales:** Scikit-learn, Pandas, Seaborn, Matplotlib.

## 📈 Conclusiones Grupales
Como equipo, concluimos que la efectividad de un modelo de IA depende tanto de la calidad de los datos como de la correcta elección del algoritmo. Este ejercicio fortaleció nuestra capacidad de análisis técnico y nuestra habilidad para colaborar en soluciones de ingeniería de sistemas.

---
**Proyecto académico desarrollado por el Equipo de Ingeniería de Sistemas - 2026**
