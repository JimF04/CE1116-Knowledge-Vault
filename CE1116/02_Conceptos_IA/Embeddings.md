---
Fecha de creación: 2026-03-17 15:06
Fecha de Modificación: 2026-03-17 15:06
tags:
  - conceptos_IA
Tema:
---


## 📚 Idea/Concepto 

Los **embeddings** son representaciones numéricas de los tokens en forma de vectores dentro de un **espacio vectorial continuo**. Cada token se asocia a un vector obtenido a partir de una **matriz de pesos aprendible**, que actúa como una tabla de búsqueda para transformar los identificadores de tokens en vectores numéricos. Estos vectores capturan relaciones semánticas entre palabras al ubicarlas en un espacio multidimensional donde la cercanía geométrica refleja similitud lingüística. La **dimensionalidad** de estos vectores (por ejemplo 512, 1024 o más) es un hiperparámetro clave que determina la capacidad del modelo para representar información semántica y su costo computacional. En arquitecturas como los **Transformers**, los embeddings se combinan con **codificaciones posicionales** para incorporar información sobre el orden de los tokens en la secuencia. Aunque los embeddings iniciales son representaciones **estáticas**, su significado se vuelve **contextual** cuando son procesados por las capas de atención del modelo.
## 📌 Puntos Claves 
- Representan tokens como vectores.  
- Capturan similitud semántica.  
- Se combinan con información posicional.

## 🔗 Connections
- [[Tokenización]]  
- [[Redes Neuronales]]

## 💡 Personal Insight 
- Son la forma en que el modelo “entiende” numéricamente las palabras.
## 🧾 Recursos (Opcional)
- 