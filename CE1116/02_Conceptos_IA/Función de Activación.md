---
Fecha de creación: 2026-03-17 15:10
Fecha de Modificación: 2026-03-17 15:10
tags:
  - conceptos_IA
Tema:
---


## 📚 Idea/Concepto 

Una **función de activación** es una función matemática aplicada a la salida de una neurona después de realizar una combinación lineal de sus entradas, expresada como $z = \sum(w_i x_i) + b$, donde $w_i$ representan los pesos y $b$ el sesgo. Su propósito es introducir **no linealidad** en la red neuronal, permitiendo que el modelo aprenda relaciones complejas entre los datos. Sin esta no linealidad, múltiples capas de la red se reducirían a una única transformación lineal incapaz de modelar patrones complejos.  
  
Durante el entrenamiento, la elección de la función de activación influye directamente en el flujo de gradientes y en la eficiencia del aprendizaje. Por esta razón, funciones como **ReLU** o **GELU** se utilizan frecuentemente en arquitecturas modernas; en particular, **GELU** introduce una activación suave basada en una aproximación probabilística relacionada con la distribución normal. Además, en muchas redes neuronales se utiliza la función **Softmax** en la capa de salida para convertir los valores de salida del modelo (logits) en probabilidades interpretables.
## 📌 Puntos Claves 
- Introduce no linealidad.  
- Mejora el aprendizaje de patrones complejos.  
- ReLU, GELU y Softmax son ejemplos importantes.
## 🔗 Connections
- [[Redes Neuronales]]

## 💡 Personal Insight 
- Sin funciones de activación, una red profunda sería equivalente a una sola transformación lineal.
## 🧾 Recursos (Opcional)
- 