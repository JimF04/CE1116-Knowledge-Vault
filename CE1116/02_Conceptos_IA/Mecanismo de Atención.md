---
Fecha de creación: 2026-03-17 15:25
Fecha de Modificación: 2026-03-17 15:25
tags:
  - conceptos_IA
Tema:
---


## 📚 Idea/Concepto 

El **mecanismo de atención** es un proceso utilizado en modelos como los Transformers que permite al modelo enfocarse en diferentes partes de una secuencia al generar representaciones contextuales. Para cada token se generan tres vectores llamados **Query**, **Key** y **Value**, obtenidos mediante proyecciones lineales aplicadas a los embeddings utilizando matrices de pesos aprendibles ($W_Q, W_K, W_V$).  
  
La relevancia entre los tokens se calcula mediante el **producto punto** entre consultas y claves ($Q \cdot K^T$). Este resultado se escala por el factor $\frac{1}{\sqrt{d_k}}$ para estabilizar los valores antes de aplicar la función **Softmax**, la cual produce una distribución de pesos de atención. Estos pesos se utilizan posteriormente para calcular una **suma ponderada** de los vectores de valor ($V$), generando una representación contextual que integra información relevante de toda la secuencia.  
  
En arquitecturas modernas, este proceso se extiende mediante **Multi-Head Attention**, donde múltiples mecanismos de atención se ejecutan en paralelo para capturar distintas relaciones dentro de la secuencia. Además, en modelos generativos se utiliza un mecanismo de **máscara causal** que evita que el modelo atienda a tokens futuros durante la generación de texto.
## 📌 Puntos Claves 
- Decide qué partes de la secuencia son relevantes.  
- Usa Query, Key y Value.  
- Genera contexto mediante pesos de atención.

## 🔗 Connections
- [[Arquitectura Transformer]]  
- [[Ventana de Contexto]]
## 💡 Personal Insight 
- Es el mecanismo que le da al modelo su capacidad de relacionar información distante.
## 🧾 Recursos (Opcional)
- 