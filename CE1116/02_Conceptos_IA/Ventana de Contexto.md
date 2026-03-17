---
Fecha de creación: 2026-03-17 15:26
Fecha de Modificación: 2026-03-17 15:26
tags:
  - conceptos_IA
Tema:
---


## 📚 Idea/Concepto 

La **ventana de contexto** es el límite máximo de **tokens** que un modelo de lenguaje puede procesar simultáneamente al generar una respuesta. Este límite actúa como la **memoria de trabajo** del modelo, determinando cuánta información previa puede utilizar para interpretar la entrada y producir una salida coherente. En modelos basados en **Transformers**, todos los tokens dentro de esta ventana se procesan conjuntamente mediante mecanismos de atención, lo que permite capturar relaciones entre diferentes partes de la secuencia.  
  
El tamaño de la ventana de contexto está directamente relacionado con el costo computacional del modelo, ya que el cálculo de atención crece aproximadamente como $O(n^2)$ con respecto al número de tokens. Además, es importante distinguir entre el **contexto de sesión** gestionado por el sistema (por ejemplo, el historial de una conversación) y el límite físico de la arquitectura del modelo. Cuando el número de tokens excede la ventana disponible, el sistema debe aplicar estrategias como el recorte o la selección parcial del historial para mantener la información dentro de la capacidad del modelo.
## 📌 Puntos Claves
- Define cuántos tokens puede procesar el modelo.  
- Funciona como memoria de trabajo.  
- Su tamaño afecta costo computacional y calidad.

## 🔗 Connections
- [[Mecanismo de Atención]]  
- [[Alucinaciones]]

## 💡 Personal Insight 
- Tener más contexto mejora coherencia, pero también encarece el procesamiento.
## 🧾 Recursos (Opcional)
- 