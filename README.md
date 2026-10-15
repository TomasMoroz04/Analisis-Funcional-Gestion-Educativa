# 🏫 Análisis y Modelado de Sistemas — Instituto de Inglés "Oxford"

Proyecto Integrador de Análisis Funcional e Ingeniería de Requisitos desarrollado para la cátedra de **Análisis de Sistemas** (3.° año de Ingeniería en Informática, UGD).

Este repositorio aloja el estudio integral del sistema de información de la Secretaría Administrativa de un instituto educativo. Aplicando la metodología de **Whitten, Bentley & Barlow**, el trabajo recorre las fases de Inspección, Estudio y Definición para relevar la situación actual, diagnosticar problemas organizacionales y modelar rigurosamente los requerimientos lógicos y funcionales de un nuevo sistema.

---

## 👥 Contexto del Proyecto y Créditos

Este trabajo refleja el **esfuerzo colaborativo de 11 estudiantes** agrupados bajo el equipo "Herederos de Schuster" durante el ciclo lectivo 2026. La versión aquí publicada es una copia parcial y "sanitizada" (datos reales modificados por confidencialidad empresarial) que captura el estado del proyecto **hasta la Fase de Definición (Especificaciones y Modelos Esenciales)**, reflejando el punto exacto hasta donde colaboré de forma directa en el equipo antes de finalizar mi participación en esta instancia.

**Equipo de Analistas (Autores originales):**
* M. Alvez
* E. Cardozo
* S. Halberstadt
* M. Kalesplaner
* A. Mango
* **Tomás Moroz** *(Curador de este repositorio)*
* A. Nielsen
* L. Ojeda
* B. Roza
* R. Ruiz
* D. Zanek

> **Nota:** Mis ex compañeros de equipo continuaron posteriormente con la cursada correlativa de *Diseño de Sistemas*, donde esta base analítica se expandió hacia la arquitectura de implementación. El mérito del modelado aquí expuesto es un logro conjunto del equipo original.

---

## 🛠️ Metodología y Frameworks Aplicados

* **Marco Analítico PIECES:** Clasificación exhaustiva de problemas, oportunidades y normas en categorías de *Prestaciones, Información, Economía, Control, Eficiencia y Servicios*.
* **Técnicas de Relevamiento:** Diseño, ejecución y transcripción de entrevistas directas, cuestionarios estructurados y análisis documental (*Investigación de Hechos*).
* **Modelado de Procesos (Análisis Estructurado):** Construcción de Diagramas de Flujo de Datos (DFD) utilizando partición de eventos (Diagrama de Contexto, DFD por Eventos, DFD Preliminar, Figura 0 y Explosiones Atómicas) siguiendo estrictamente las convenciones de balanceo y nivelación de Edward Yourdon.
* **Modelado de Datos:** Diseño del modelo conceptual de la nueva solución mediante un Diagrama de Entidad-Relación (DER) extendido.
* **Especificación Lógica de Procesos (ELP):** Documentación formal, rigurosa y sin ambigüedades de los procesos atómicos utilizando Lenguaje Estructurado (Pseudocódigo), Pre/Post Condiciones y Árboles de Decisión.
* **Trazabilidad:** Matrices de ponderación matemática de urgencia/visibilidad y Matriz de Trazabilidad bidireccional entre las necesidades del nuevo sistema y los problemas de negocio originales.

---

## ⚙️ Fases Documentadas del Proyecto

### 1️⃣ Fase de Inspección y Viabilidad
* Relevamiento inicial del organigrama mediante entrevistas.
* Identificación del mapa de procesos organizacionales y delimitación de la frontera del sistema.
* Matriz preliminar PIECES y evaluación de viabilidad (operativa, técnica, económica y de calendario) para determinar la continuidad del proyecto.

### 2️⃣ Fase de Estudio del Sistema Actual ("As-Is")
* Documentación detallada del funcionamiento actual estructurada en bloques elementales: *Personas, Actividades, Datos y Tecnología*.
* Modelado esencial del sistema actual mediante DFDs para detectar empíricamente redundancias, cuellos de botella y controles deficientes (por ejemplo, duplicación de inscripciones de alumnos en múltiples horarios, ocupación de cupos ficticios y demoras de 4 horas en rastrear el historial de docentes).
* Análisis de causas y efectos, y formulación de una función de priorización.

### 3️⃣ Fase de Definición del Nuevo Sistema ("To-Be")
* Establecimiento de los objetivos mensurables del nuevo sistema y priorización de requerimientos (obligatorios, deseables, opcionales).
* Construcción del modelo esencial del sistema propuesto, completamente agnóstico de la tecnología de implementación.
* Construcción del **Diccionario de Datos** del nuevo sistema (almacenes, flujos de datos estructurados y elementos de datos atómicos).
* Especificación de la Lógica de Procesos (ELP) para guiar al futuro equipo de desarrollo de software y arquitectos de bases de datos.

---

## 📂 Estructura del Repositorio

* `Documento_TPI_Analisis_Funcional.pdf` — El informe "sanitizado" completo con las Fases de Inspección, Estudio y Definición, matrices de análisis, diccionarios de datos y especificaciones.
* `/diagramas` — Carpeta con las exportaciones en alta calidad de los principales modelos gráficos desarrollados en Lucidchart:
  * Diagramas de Contexto (Sistema Actual y Nuevo Sistema).
  * DFD de Figura 0 (Balanceado y nivelado).
  * Diagrama de Entidad-Relación (DER).
  * Diagrama de Conexión de Puestos (Modelo de Redes).
