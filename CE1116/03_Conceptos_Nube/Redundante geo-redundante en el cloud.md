---
Fecha de creación: 2026-04-30 14:56
Fecha de Modificación: 2026-04-30 14:56
tags:
  - conceptos_Nube
Tema:
---


## 📚 Idea/Concepto 

La redundancia geo-redundante en el cloud consiste en replicar datos y servicios entre regiones completamente independientes, cada una formada por múltiples zonas de disponibilidad con energía, red y enfriamiento autónomos. Las regiones están conectadas mediante redes troncales intercontinentales que permiten la sincronización y recuperación ante fallas, aunque la distancia introduce latencia que limita el uso de replicación síncrona y puede requerir consistencia eventual. Este modelo garantiza continuidad operativa incluso ante la pérdida total de una región, mediante mecanismos globales de redirección de tráfico como Anycast o GSLB, y sistemas distribuidos capaces de tolerar particiones según los compromisos del Teorema CAP. Debido al desacoplamiento entre cómputo y almacenamiento, los datos pueden persistir de manera independiente al estado de los nodos locales. Este enfoque representa el nivel más alto de resiliencia, diseñado para soportar desastres de escala continental mientras mantiene métricas extremas de durabilidad y disponibilidad.
## 📌 Puntos Claves (Opcional)
- Multi-región global
- Máxima resiliencia
- Replicación con latencia alta

## 🔗 Connections
- [[Redundante en zona en el cloud]] 
- [[Cloud Público]] 
- [[Cloud Híbrido (Hybrid Cloud)]] 
- [[Escalamiento horizontal y vertical en el cloud]] 

## 💡 Personal Insight (Opcional)
- Es el nivel máximo de resiliencia cloud.
## 🧾 Recursos (Opcional)
- 