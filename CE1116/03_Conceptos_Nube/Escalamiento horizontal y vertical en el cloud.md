---
Fecha de creación: 2026-04-30 14:55
Fecha de Modificación: 2026-04-30 14:55
tags:
  - conceptos_Nube
Tema:
---


## 📚 Idea/Concepto 

El escalamiento en la nube se basa en dos enfoques complementarios. El escalamiento vertical aumenta la capacidad de un único servidor añadiendo más CPU, memoria o almacenamiento, aunque está limitado por el hardware físico y suele requerir interrupciones para aplicar cambios. Por otro lado, el escalamiento horizontal añade múltiples instancias idénticas que comparten la carga mediante un balanceador de tráfico, favoreciendo el crecimiento sin afectar la continuidad del servicio. En arquitecturas modernas, especialmente aquellas diseñadas como stateless y con almacenamiento desacoplado, ambos modelos se combinan con mecanismos de elasticidad que ajustan automáticamente la capacidad (Scale Out/Up o Scale In/Down) en función de métricas operativas como CPU, RAM o latencia, optimizando rendimiento y costos.
## 📌 Puntos Claves (Opcional)
- Vertical = más potencia en una máquina
- Horizontal = más máquinas
- Horizontal requiere balanceador
- Elasticidad automática (Scale In/Out)

## 🔗 Connections
- [[Cloud Público]] 
- [[IaaS vs PaaS vs SaaS]] 
- [[Virtual Private Cloud (VPC)]] 
- [[Redundante localmente en el cloud]] 
- [[Redundante en zona en el cloud]] 
- [[Redundante geo-redundante en el cloud]] 

## 💡 Personal Insight (Opcional)
- El horizontal es clave para sistemas modernos sin downtime.
## 🧾 Recursos (Opcional)
- 