---
Fecha de creación: 2026-03-17 15:02
Fecha de Modificación: 2026-03-17 15:02
tags:
  - conceptos_IA
Tema:
---


## 📚 Idea/Concepto 

La **tokenización** es el proceso de preprocesamiento mediante el cual un texto de entrada se divide en unidades discretas llamadas **tokens**. Estos tokens pueden representar palabras completas, fragmentos de palabras (subpalabras) o caracteres individuales, dependiendo del método de tokenización utilizado. En modelos modernos de lenguaje, algoritmos como **Byte Pair Encoding (BPE)** permiten descomponer palabras desconocidas en fragmentos frecuentes para mejorar la cobertura del vocabulario. Cada token se asocia posteriormente con un **identificador numérico** dentro de un vocabulario predefinido, permitiendo transformar el lenguaje natural en una representación numérica que puede ser procesada por modelos de aprendizaje automático. Además, se utilizan **tokens especiales** para gestionar límites de secuencia, términos desconocidos y operaciones de procesamiento por lotes durante el entrenamiento y la inferencia del modelo.
## 📌 Puntos Claves 
- Divide el texto en tokens.  
- Convierte lenguaje en unidades procesables.  
- Puede usar palabras, subpalabras o caracteres.

## 🔗 Connections
- [[Embeddings]]  

## 💡 Personal Insight 
- Es el primer paso del pipeline de un LLM: texto → tokens → vectores.
## 🧾 Recursos 
- 