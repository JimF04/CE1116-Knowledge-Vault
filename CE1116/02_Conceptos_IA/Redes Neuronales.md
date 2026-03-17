---
Fecha de creación: 2026-03-17 15:09
Fecha de Modificación: 2026-03-17 15:09
tags:
  - conceptos_IA
Tema:
---


## 📚 Idea/Concepto 

  
Una **red neuronal** es un modelo computacional compuesto por capas de **neuronas artificiales** que implementan funciones parametrizadas para transformar vectores de entrada en representaciones internas. Cada neurona realiza una combinación lineal de las entradas mediante **pesos** y un **sesgo** ($W \cdot x + b$), seguida de una **función de activación no lineal** que permite modelar relaciones complejas en los datos. Estas operaciones se implementan mediante **álgebra lineal** y multiplicaciones de matrices, lo que facilita el entrenamiento eficiente en paralelo. Durante el entrenamiento, los **parámetros aprendibles** ($w, b$) se ajustan mediante el algoritmo de **retropropagación** (backpropagation), que calcula gradientes de una **función de costo** y optimiza los pesos mediante métodos como el descenso de gradiente. Además, el diseño del modelo depende de **hiperparámetros** definidos por el usuario, como la tasa de aprendizaje o el número de capas, que controlan el proceso de entrenamiento y la capacidad del modelo.
## 📌 Puntos Claves 
- Transforman entradas en representaciones internas.  
- Usan pesos, sesgos y activaciones.  
- Aprenden ajustando parámetros.

## 🔗 Connections
- [[Embeddings]]  
- [[Función de Activación]]  
- [[Arquitectura Transformer]]
## 💡 Personal Insight 
- Las redes neuronales permiten aproximar funciones complejas a partir de datos.
## 🧾 Recursos (Opcional)
- 