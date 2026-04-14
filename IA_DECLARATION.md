# Bitácora de Uso de IA Generativa (ai-log.md)
**Equipo:** PCABoys  
**Proyecto:** El Ciclo de la Inacción: Agua, Salud y Pobreza en México

---

## 1. Herramientas Utilizadas
* **ChatGPT (GPT-4o) / Claude 3.5 Sonnet:** Utilizado para la estructuración de la narrativa y depuración de código.
* **GitHub Copilot:** Utilizado para el autocompletado de funciones de visualización en Python.

---

## 2. Registro de Interacciones Significativas

> *Instrucción: Se debe registrar cada interacción que haya definido el rumbo del proyecto.*

### Interacción 1: Optimización del cruce de datos (Data Wrangling)
* **Prompt utilizado:** "Tengo un dataframe de CONAGUA con coordenadas y uno de la SSA con casos de enfermedades por municipio. ¿Cómo puedo hacer un merge espacial eficiente usando GeoPandas para asignar cada punto de medición al municipio correspondiente?"
* **Resultado bruto de la IA:** [Aquí pegarías el bloque de código inicial que te dio la IA]
* **Modificaciones realizadas:** La IA sugirió un `sjoin` básico, pero tuve que modificar el sistema de referencia de coordenadas (CRS) a EPSG:4326 para que coincidiera con mis datos reales de CONAGUA.
* **Decisión/Justificación:** Se decidió usar esta lógica porque hacer el cruce manual por nombres de municipios generaba errores debido a las tildes y variaciones en la escritura de los catálogos oficiales.

### Interacción 2: Diseño de la Tesis Narrativa (Storytelling)
* **Prompt utilizado:** "Ayúdame a conectar los ODS 1, 3 y 6 con la frase 'la inacción es más cara'. Dame 3 argumentos basados en economía de la salud."
* **Resultado bruto de la IA:** [Aquí pegarías los puntos que te dio la IA]
* **Modificaciones realizadas:** Se descartó el argumento sobre turismo y nos enfocamos exclusivamente en la pérdida de productividad laboral y gastos hospitalarios de bolsillo en familias vulnerables.
* **Decisión/Justificación:** Queríamos que la narrativa fuera coherente con los datos de CONEVAL que ya tenemos procesados.

---

## 3. Declaración de Narrativa Propia
Conforme a la sección 3.3 del reglamento, el equipo PCABoys declara que, si bien se utilizaron herramientas de IA para refinar la estructura y el código, todas las conclusiones, la interpretación de los resultados y la narrativa final del dashboard son producto del análisis crítico de los integrantes. La IA actuó como un facilitador técnico, no como el autor de la investigación.

---
**Fecha de última actualización:** 13 de abril de 2026