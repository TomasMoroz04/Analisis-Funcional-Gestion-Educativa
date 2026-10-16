<h1 align="center">🏫 Análisis y Modelado de Sistemas</h1>
<h3 align="center">Instituto de Inglés «Oxford»</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Disciplina-Análisis%20de%20Sistemas-6C5CE7?style=for-the-badge" alt="Análisis de Sistemas">
  <img src="https://img.shields.io/badge/Metodología-PIECES-0A7EA4?style=for-the-badge" alt="PIECES">
  <img src="https://img.shields.io/badge/Modelado-DFD%20%7C%20DER-00897B?style=for-the-badge" alt="DFD y DER">
  <img src="https://img.shields.io/badge/Documentación-PDF-B31B1B?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="PDF">
</p>

Proyecto Integrador de **Análisis Funcional e Ingeniería de Requisitos** desarrollado para la cátedra de **Análisis de Sistemas** (3.° año de Ingeniería en Informática, UGD).

Este repositorio reúne el estudio del sistema de información de la Secretaría Administrativa de un instituto educativo. Aplicando la metodología de **Whitten, Bentley y Barlow**, el trabajo recorre las fases de Inspección, Estudio y Definición para relevar la situación actual, diagnosticar problemas organizacionales y modelar los requerimientos lógicos y funcionales de un nuevo sistema.

---

## 📑 Índice

- [Contexto y créditos](#-contexto-del-proyecto-y-créditos)
- [Metodología y herramientas](#-metodología-y-frameworks-aplicados)
- [Fases documentadas](#-fases-documentadas-del-proyecto)
- [Contenido del repositorio](#-estructura-del-repositorio)

---

## 👥 Contexto del proyecto y créditos

Este trabajo refleja el **esfuerzo colaborativo de 11 estudiantes**, agrupados bajo el equipo **«Herederos de Schuster»** durante el ciclo lectivo 2026.

La versión publicada es una copia parcial y **sanitizada** —se modificaron datos reales por confidencialidad empresarial— que captura el estado del proyecto hasta la **Fase de Definición (especificaciones y modelos esenciales)**. Representa el punto hasta el cual participé directamente en el equipo antes de finalizar mi participación en esta instancia.

**Equipo de analistas — autores originales:**

- M. Alvez
- E. Cardozo
- S. Halberstadt
- M. Kalesplaner
- A. Mango
- **Tomás Moroz** — curador de este repositorio
- A. Nielsen
- L. Ojeda
- B. Roza
- R. Ruiz
- D. Zanek

> **Nota de autoría:** mis excompañeros continuaron posteriormente con la cursada correlativa de Diseño de Sistemas, donde esta base analítica se expandió hacia la arquitectura de implementación. El modelado aquí expuesto es un logro conjunto del equipo original.

---

## 🛠️ Metodología y frameworks aplicados

- **Marco analítico PIECES:** clasificación de problemas, oportunidades y normas en las categorías de Prestaciones, Información, Economía, Control, Eficiencia y Servicios.
- **Técnicas de relevamiento:** diseño, ejecución y transcripción de entrevistas directas, cuestionarios estructurados y análisis documental mediante investigación de hechos.
- **Modelado de procesos:** construcción de Diagramas de Flujo de Datos (DFD) mediante partición de eventos: Diagrama de Contexto, DFD por Eventos, DFD Preliminar, Figura 0 y explosiones atómicas. Se siguen las convenciones de balanceo y nivelación de Edward Yourdon.
- **Modelado de datos:** diseño conceptual de la solución mediante un Diagrama de Entidad-Relación (DER) extendido.
- **Especificación Lógica de Procesos (ELP):** documentación formal de procesos atómicos mediante lenguaje estructurado (pseudocódigo), precondiciones, poscondiciones y árboles de decisión.
- **Trazabilidad:** matrices de ponderación de urgencia y visibilidad, y matriz de trazabilidad bidireccional entre las necesidades del sistema propuesto y los problemas originales del negocio.

---

## ⚙️ Fases documentadas del proyecto

### 1️⃣ Fase de inspección y viabilidad

- Relevamiento inicial del organigrama mediante entrevistas.
- Identificación del mapa de procesos organizacionales y delimitación de la frontera del sistema.
- Elaboración de la matriz preliminar PIECES y evaluación de viabilidad operativa, técnica, económica y de calendario.

### 2️⃣ Fase de estudio del sistema actual (*As-Is*)

- Documentación del funcionamiento actual a partir de cuatro bloques: **Personas, Actividades, Datos y Tecnología**.
- Modelado esencial mediante DFD para detectar redundancias, cuellos de botella y controles deficientes.
- Análisis de causas y efectos y formulación de una función de priorización.

Entre los ejemplos analizados se encuentran la duplicación de inscripciones de alumnos en varios horarios, la ocupación ficticia de cupos y las demoras en rastrear el historial de docentes.

### 3️⃣ Fase de definición del nuevo sistema (*To-Be*)

- Definición de objetivos mensurables y priorización de requerimientos obligatorios, deseables y opcionales.
- Construcción del modelo esencial de la solución, independiente de la tecnología de implementación.
- Elaboración del **Diccionario de Datos**: almacenes, flujos estructurados y elementos atómicos.
- Especificación de la lógica de procesos para orientar al futuro equipo de desarrollo y a los responsables del diseño de la base de datos.

---

## 📂 Estructura del repositorio

- **`Documento_TPI_Analisis_Funcional.pdf`** — informe sanitizado con las fases de Inspección, Estudio y Definición, matrices de análisis, diccionarios de datos y especificaciones.
- **`/diagramas`** — carpeta con exportaciones en alta calidad de los principales modelos gráficos realizados en Luciddchart, incluidos:
  - Diagramas de Contexto del sistema actual y del nuevo sistema.
  - DFB de Figura 0, balanceado y nivelado.
  - Diagrama de Entidad-Relación (DER).
  - Diagrama de Conexión de Puestos (modelo de redes).

---

<p align="center"><b>Análisis de Sistemas ² Ingeniería de Requisitos ² Modelado funcional</b></p>
