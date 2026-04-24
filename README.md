🤖 Detección Inteligente de Anomalías en Infraestructura

🎯 Objetivo del Proyecto
Implementar un modelo de Machine Learning No Supervisado para identificar comportamientos anómalos en métricas de servidores (CPU/Memoria). Este sistema permite detectar fallas de hardware, ataques o fugas de memoria que no serían detectadas por umbrales estáticos tradicionales.

🛠️ Tecnologías

Python: Lenguaje principal.
Scikit-Learn: Uso del algoritmo Isolation Forest.
Matplotlib: Visualización de clusters y outliers.

💡 ¿Cómo funciona?

A diferencia de un sistema de alertas tradicional, este modelo utiliza un Bosque de Aislamiento. El algoritmo mide qué tan "fácil" es aislar un punto de dato. Si un punto se aisla rápidamente, se etiqueta como anomalía. Esto permite detectar incidentes complejos donde el CPU y la Memoria suben en conjunto de forma sospechosa.

🚀 Impacto en el Negocio

Reducción de Fatiga por Alertas: Solo se notifican desviaciones estadísticas reales.
Mantenimiento Proactivo: Identificación de patrones previos a una caída total del servicio.
