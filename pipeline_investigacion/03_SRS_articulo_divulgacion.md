# SRS: Artículo de Divulgación "Del Prompt al Pipeline"

**Versión:** 1.2  
**Fecha:** 2025-03-12  
**Autor:** Omar Francisco Velázquez Juárez  
**Estado:** Completado

---

## 1. Introducción

### 1.1 Propósito

Producir un artículo de divulgación científica que presente el pipeline de 8 etapas para uso estructurado de herramientas de IA en investigación y docencia, dirigido a la comunidad académica de Global University.

### 1.2 Alcance

**Incluye:**
- Artículo de ~2 páginas en formato Markdown
- Referencias académicas en formato APA (2023-2025)
- Licencia Creative Commons BY 4.0
- Instrumentos de soporte del pipeline demostrados en el proceso

**No incluye:**
- Versión en inglés
- Diseño gráfico o maquetación final
- Video o podcast derivado (fase posterior con NotebookLM)

### 1.3 Definiciones

| Término | Definición |
|---------|------------|
| LLM | Large Language Model - Modelo de lenguaje grande |
| Pipeline | Flujo de trabajo estructurado con etapas definidas |
| Documentation as Code | Práctica de versionar documentación en repositorios Git |
| SRS | Software Requirements Specification - Especificación de requerimientos |
| CR | Change Request - Control de cambios |

### 1.4 Referencias

- Respuestas a preguntas guía (sesión 2025-03-12)
- 12 referencias académicas validadas vía Google Scholar
- Pipeline personal del autor para investigación doctoral

---

## 2. Descripción General

### 2.1 Contexto

Este artículo es el primer producto público que documenta el pipeline de investigación desarrollado por el autor. Se publica en el sitio web de Global University como contribución a la comunidad docente.

### 2.2 Objetivo comunicacional

Convencer al lector de que:
1. El uso casual de IA (prompting ad-hoc) es insuficiente para trabajo académico serio
2. Existe una alternativa estructurada y reproducible
3. Esta alternativa es aprendible y transferible al aula

### 2.3 Audiencia

| Segmento | Características | Necesidad |
|----------|-----------------|-----------|
| Profesores de ingeniería | Experiencia técnica variable, presión por integrar IA | Metodología práctica, no teoría abstracta |
| Estudiantes avanzados | Usan IA pero sin estructura | Marco que legitime y mejore su uso |
| Administradores académicos | Preocupados por integridad académica | Evidencia de que hay formas responsables de usar IA |

### 2.4 Restricciones

1. **Extensión:** Máximo 2 páginas (~1500 palabras)
2. **Tono:** Divulgativo riguroso, primera persona, sin jerga innecesaria
3. **Referencias:** Solo literatura 2023-2025, verificable
4. **Formato:** Markdown para publicación web
5. **Tiempo:** Completar en una sesión de trabajo

---

## 3. Requerimientos Específicos

### 3.1 Requerimientos de Contenido

#### REQ-CON-001: Desmitificación de IA
- **Descripción:** Explicar que LLM se entrenan, no se programan; que "inteligencia" es término de marketing pero el campo es legítimo
- **Criterio de aceptación:** Lector entiende la distinción sin sentirse condescendido
- **Prioridad:** Alta

#### REQ-CON-002: Explicación de alucinaciones
- **Descripción:** Presentar alucinaciones como problema técnico/metodológico, no ético
- **Criterio de aceptación:** Cita al menos 2 fuentes académicas que soporten la explicación
- **Prioridad:** Alta

#### REQ-CON-003: Presentación del pipeline
- **Descripción:** Describir las 8 etapas con suficiente detalle para que el lector entienda el flujo
- **Criterio de aceptación:** Cada etapa tiene nombre, herramienta, y propósito claro
- **Prioridad:** Alta

#### REQ-CON-004: Transferencia al aula
- **Descripción:** Explicar cómo el pipeline aplica a contexto educativo
- **Criterio de aceptación:** Incluye criterios concretos de evaluación
- **Prioridad:** Alta

#### REQ-CON-005: Cierre memorable
- **Descripción:** Concluir con llamado a la acción y reflexión sobre el cambio de práctica
- **Criterio de aceptación:** Última sección tiene arco narrativo completo, no lista de ideas sueltas
- **Prioridad:** Media

### 3.2 Requerimientos de Formato

#### REQ-FOR-001: Estructura de secciones
- **Descripción:** 5 secciones con títulos descriptivos
- **Estructura aprobada:**
  1. La IA no piensa, predice
  2. El costo de trabajar sin estructura
  3. Un pipeline de ocho etapas
  4. De la investigación al aula
  5. Hacia una práctica madura
- **Prioridad:** Alta

#### REQ-FOR-002: Referencias APA
- **Descripción:** Todas las citas en formato APA 7ma edición
- **Criterio de aceptación:** Referencias completas al final, citas en texto con (Autor, Año)
- **Prioridad:** Alta

#### REQ-FOR-003: Licencia
- **Descripción:** Incluir declaración de licencia CC BY 4.0
- **Criterio de aceptación:** Texto de licencia y URL al final del documento
- **Prioridad:** Media

### 3.3 Requerimientos de Calidad

#### REQ-CAL-001: Fluidez de lectura
- **Descripción:** El texto debe leerse naturalmente, sin saltos abruptos ni tono robótico
- **Criterio de aceptación:** Revisión subjetiva del autor confirma tono conversacional
- **Prioridad:** Alta

#### REQ-CAL-002: Precisión técnica
- **Descripción:** Conceptos técnicos deben ser correctos y verificables
- **Criterio de aceptación:** Cada afirmación técnica tiene respaldo en referencias o conocimiento del autor
- **Prioridad:** Alta

#### REQ-CAL-003: Ausencia de presunción
- **Descripción:** El texto no debe sonar como autopromoción
- **Criterio de aceptación:** Sección 4 presenta propuesta sin tono de "miren lo que yo hago"
- **Prioridad:** Alta

---

## 4. Criterios de Aceptación Global

| ID | Criterio | Verificación |
|----|----------|--------------|
| CA-001 | Extensión ~2 páginas | Conteo de palabras: 1400-1600 |
| CA-002 | 5 secciones completas | Revisión de estructura |
| CA-003 | Mínimo 10 referencias | Conteo en sección Referencias |
| CA-004 | Tono consistente | Lectura completa sin detectar secciones "robóticas" |
| CA-005 | Pipeline claramente explicado | Lector puede enumerar las 8 etapas después de leer |
| CA-006 | Aplicación docente clara | Sección 4 incluye criterios de evaluación concretos |

---

## 5. Entregables

| ID | Entregable | Formato | Ubicación |
|----|------------|---------|-----------|
| E-001 | Artículo final | .md | /outputs/articulo_pipeline_ia.md |
| E-002 | Versión Word (opcional) | .docx | /outputs/articulo_pipeline_ia.docx |
| E-003 | Instrumentos de soporte | .md, .bib | /outputs/instrumentos/ |

---

## 6. Historial de Versiones

| Versión | Fecha | Cambios |
|---------|-------|---------|
| 1.0 | 2025-03-12 | Versión inicial con requerimientos base |
| 1.1 | 2025-03-12 | Ajuste REQ-CON-001 tras clarificación sobre IA/mercadotecnia |
| 1.2 | 2025-03-12 | Agregado REQ-CAL-003 tras feedback sobre tono presuntuoso en sección 4 |

---

## 7. Aprobación

| Rol | Nombre | Estado | Fecha |
|-----|--------|--------|-------|
| Autor | Omar Francisco Velázquez Juárez | Aprobado | 2025-03-12 |

---

## Licencia

Este documento está licenciado bajo Creative Commons Atribución 4.0 Internacional (CC BY 4.0).
