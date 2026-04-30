---
Fecha de creación: 2026-04-30 14:56
Fecha de Modificación: 2026-04-30 14:56
tags:
  - conceptos_Nube
Tema:
---


## 📚 Idea/Concepto 

La redundancia local en el cloud consiste en replicar datos o servicios dentro del mismo datacenter utilizando mecanismos de replicación sincrónica que aseguran que cada escritura se distribuya de inmediato entre distintos dominios de falla, como discos, nodos o racks independientes, antes de ser confirmada. Este enfoque proporciona una alta durabilidad del dato frente a fallas aisladas de hardware dentro del edificio y suele expresarse mediante métricas de durabilidad ("nueves"). Sin embargo, su alcance se limita a la infraestructura física local del datacenter y no ofrece protección ante fallas que afecten a una zona de disponibilidad completa ni ante eventos de mayor escala.
## 📌 Puntos Claves (Opcional)
- Replicación en un solo datacenter
- Alta durabilidad local
- Usa dominios de falla
- No protege fallos de zona

## 🔗 Connections
- [[Cloud Público]] 
- [[Escalamiento horizontal y vertical en el cloud]] 
- [[Redundante en zona en el cloud]] 
- [[Redundante geo-redundante en el cloud]] 

## 💡 Personal Insight (Opcional)
- Es la primera capa de resiliencia real.
## 🧾 Recursos (Opcional)
- 