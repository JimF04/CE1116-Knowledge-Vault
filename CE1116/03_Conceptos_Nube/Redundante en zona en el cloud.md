---
Fecha de creación: 2026-04-30 14:56
Fecha de Modificación: 2026-04-30 14:56
tags:
  - conceptos_Nube
Tema:
---


## 📚 Idea/Concepto 

La redundancia en zona en el cloud consiste en desplegar y replicar datos y servicios entre múltiples zonas de disponibilidad dentro de una misma región. Cada zona está formada por uno o más datacenters aislados entre sí, con energía, red y enfriamiento independientes para evitar fallas en cascada. Este aislamiento permite que una aplicación continúe operando incluso si una zona queda inactiva. La replicación puede ser síncrona o asíncrona, lo que introduce diferencias en latencia y en los tiempos de recuperación. Además, la separación entre cómputo y almacenamiento asegura que los datos permanezcan accesibles aunque un nodo o una zona falle. La resiliencia alcanzada se mide habitualmente mediante métricas de disponibilidad y durabilidad que reflejan la robustez del diseño multizona.
## 📌 Puntos Claves (Opcional)
- Multi-zona dentro de una región
- Aislamiento físico entre zonas
- Replicación síncrona/asíncrona
- Alta disponibilidad regional

## 🔗 Connections
- [[Redundante localmente en el cloud]] 
- [[Redundante geo-redundante en el cloud]] 
- [[Cloud Público]] 
- [[Escalamiento horizontal y vertical en el cloud]] 

## 💡 Personal Insight (Opcional)
- Es el estándar de alta disponibilidad en cloud moderno.
## 🧾 Recursos (Opcional)
- 