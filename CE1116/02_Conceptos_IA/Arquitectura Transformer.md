---
Fecha de creación: 2026-03-17 15:12
Fecha de Modificación: 2026-03-17 15:12
tags:
  - conceptos_IA
Tema:
---


## 📚 Idea/Concepto 

La **arquitectura Transformer** es un modelo de redes neuronales diseñado para procesar secuencias de datos mediante mecanismos de **atención**. A diferencia de las arquitecturas recurrentes, elimina la dependencia de la recurrencia y permite procesar los elementos de una secuencia en paralelo durante el entrenamiento. Su componente central es el **Multi-Head Attention**, que utiliza proyecciones lineales para generar los vectores **Query**, **Key** y **Value** ($Q, K, V$), permitiendo que el modelo capture relaciones entre diferentes posiciones de la secuencia desde múltiples perspectivas semánticas. En el cálculo de la atención, se utiliza un factor de escalamiento $\sqrt{d_k}$ para estabilizar los valores antes de aplicar la función **Softmax**.  
  
Además, debido a la ausencia de recurrencia, el Transformer incorpora **codificaciones posicionales** para representar el orden de los tokens dentro de la secuencia. Cada bloque del modelo también incluye **conexiones residuales**, **normalización de capas** (Layer Normalization) y **redes Feed-Forward** que procesan cada posición de la secuencia de forma independiente. Estos componentes permiten estabilizar el entrenamiento y mejorar la capacidad del modelo para aprender representaciones complejas del lenguaje.
## 📌 Puntos Claves 
- Procesa secuencias con atención.  
- Permite paralelismo en entrenamiento.  
- Usa Q, K, V y codificaciones posicionales.

## 🔗 Connections
- [[Redes Neuronales]]  
- [[Mecanismo de Atención]]

## 💡 Personal Insight 
- Es la arquitectura que hizo posible el salto moderno en modelos de lenguaje.
## 🧾 Recursos (Opcional)
- 