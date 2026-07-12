# Diseño de Métricas para un Sistema de Análisis de Sentimiento

Implementación de un esquema de métricas para evaluar un sistema de análisis de sentimiento aplicado a la atención al cliente en Twitter.

Proyecto académico realizado en el marco del curso **Data Science III – Procesamiento de Lenguaje Natural (NLP)**

**Coderhouse**

**Año:** 2026

**Moreno, Silvina Danisa**

📧 silvina.danisa.moreno@gmail.com

🐙 GitHub: **SilvinaMoreno**

---

# Descripción

El objetivo de este proyecto es diseñar un esquema de métricas que permita evaluar el desempeño de un sistema de análisis de sentimiento aplicado a consultas de clientes realizadas a través de Twitter.

La propuesta busca demostrar cómo el Procesamiento de Lenguaje Natural puede utilizarse para transformar grandes volúmenes de texto en información útil para mejorar la atención al cliente y apoyar la toma de decisiones.

---

# Caso de uso

Se plantea el escenario de una empresa que recibe miles de consultas diarias mediante Twitter relacionadas con soporte técnico, facturación y reclamos.

Debido al elevado volumen de mensajes, el análisis manual resulta poco eficiente. Mediante un sistema de análisis de sentimiento es posible detectar automáticamente consultas críticas, priorizar reclamos y generar indicadores operativos para el área de soporte.

---

# Objetivos

- Detectar automáticamente consultas con sentimiento negativo.
- Priorizar reclamos críticos.
- Reducir el tiempo de respuesta.
- Medir la calidad del servicio.
- Automatizar el procesamiento de consultas.

---

# Dataset

Para contextualizar el caso de uso se tomó como referencia el dataset público:

**Customer Support on Twitter**

https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter

---

# Métricas propuestas

- Accuracy
- Tiempo promedio de respuesta
- Cobertura
- Índice de sentimiento
- Porcentaje de consultas críticas

Cada una de estas métricas permite evaluar tanto el rendimiento técnico del sistema como su impacto sobre el negocio.

---

# Recolección de datos

La información proviene de consultas realizadas por clientes mediante Twitter.

El pipeline realiza automáticamente:

- Recepción de consultas
- Limpieza del texto
- Análisis de sentimiento
- Clasificación automática
- Almacenamiento
- Generación de indicadores

---

# Beneficios para el negocio

- Reducción del tiempo de respuesta.
- Priorización automática de reclamos.
- Mejora en la experiencia del cliente.
- Automatización del soporte.
- Generación de indicadores para la toma de decisiones.

---

# Escalabilidad

El sistema puede procesar miles de consultas de forma automática.

En escenarios reales resulta recomendable utilizar arquitecturas escalables y modelos basados en Transformers para mejorar la precisión y soportar grandes volúmenes de información.

---

# Limitaciones

El análisis de sentimiento basado en reglas o modelos simples puede presentar dificultades para interpretar sarcasmos, ironías o lenguaje informal.

En producción sería recomendable utilizar modelos supervisados o arquitecturas basadas en Transformers.

---

# Tecnologías utilizadas

- Python
- Pandas
- NumPy
- TextBlob
- Google Colab

---

# Autor

**Silvina Danisa Moreno**

GitHub: https://github.com/SilvinaMoreno

Data Science III

Coderhouse

2026
