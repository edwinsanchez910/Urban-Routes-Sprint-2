# Urban-Routes-Sprint-2# 🧠 QA Engineering: Diseño de Pruebas y Lógica de Negocio - Urban Routes

## 📋 Descripción del Proyecto
A diferencia de la fase inicial enfocada en interfaz, en este **Sprint 2** el objetivo principal fue el **Diseño de Estrategias de Prueba** y la **Validación de Lógica de Negocio**. 

Me enfoqué en desglosar el comportamiento interno de la aplicación para asegurar que los cálculos de tarifas, tiempos de viaje y validaciones de formularios críticos funcionen con precisión matemática bajo cualquier escenario.

---

## 🛠️ Metodologías y Técnicas Aplicadas
Para garantizar una cobertura total sin redundancias, apliqué las siguientes técnicas de diseño:

* **Análisis de Clases de Equivalencia:** Clasificación de datos de entrada (nombres, teléfonos, fechas) para optimizar el número de pruebas.
* **Análisis de Valores Límite:** Pruebas críticas en los bordes de los campos (ej. nombres de 2 y 14 caracteres) para detectar errores de desbordamiento o restricción.
* **Validación de Algoritmos:** Comprobación de la lógica de velocidad promedio basada en ventanas de tiempo (Horarios punta vs. Horarios valle).

---

## 🗺️ Modelado y Análisis Visual
Para comprender la arquitectura de la información, desarrollé la siguiente documentación técnica:

* **Mapa Mental:** Estructuración de cada componente de la aplicación y sus dependencias.
* **Diagrama de Flujo Lógico:** Modelado del algoritmo de cálculo de velocidad y tiempo de llegada según la hora de salida.

> 📂 *Puedes encontrar estos diagramas detallados en la carpeta `/documentacion-visual` de este repositorio.*

---

## 🧪 Casos de Prueba y Resultados (Muestra)
Se diseñó una suite de pruebas enfocada en la precisión del sistema. Algunos casos clave incluyen:

| ID | Escenario de Prueba | Resultado Esperado |
| :--- | :--- | :--- |
| **P-1** | Cálculo de viaje a las 23:59h | Velocidad base / Tarifa estándar |
| **P-2** | Cálculo de viaje a las 07:59h | Aplicación de velocidad media (1,86 min) |
| **P-3** | Validación de Nombre (Mín/Máx) | Aceptación de 2 a 14 caracteres |

---

## 🚀 Conclusión
Este repositorio demuestra mi capacidad para pasar de la ejecución visual al **análisis técnico profundo**, diseñando la lógica que asegura la calidad del software desde su estructura interna.
