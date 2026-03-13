# Insumos para NotebookLM: Pipeline de IA para Investigación y Docencia

**Proyecto:** Artículo "Del prompt al pipeline"  
**Fecha de preparación:** 2025-03-12  
**Autor:** Omar Francisco Velázquez Juárez

---

## Instrucciones de Uso

1. Subir este documento a NotebookLM como fuente principal
2. Opcionalmente, subir también el artículo completo (.md)
3. Usar las secciones de abajo para generar:
   - Audio Overview (podcast)
   - Presentación de slides
   - Guía de estudio
   - FAQs

---

## Contexto del Proyecto

### Resumen ejecutivo

Este proyecto presenta un pipeline de 8 etapas para usar herramientas de inteligencia artificial de forma estructurada en investigación académica y docencia universitaria. El pipeline transforma el uso casual de IA (prompting ad-hoc) en una práctica metodológica con trazabilidad, reproducibilidad y criterios de evaluación claros.

### Problema que aborda

Los modelos de lenguaje grandes (LLM) como ChatGPT, Claude o Gemini se han integrado masivamente en el trabajo académico. Sin embargo, la mayoría de usuarios los emplean sin estructura: prompts vagos, aceptación acrítica de respuestas, imposibilidad de reproducir el proceso meses después. Las alucinaciones (respuestas plausibles pero falsas) son frecuentes y pasan desapercibidas cuando no hay validación sistemática.

### Pregunta central

¿Cómo transformar el uso de herramientas de IA de una práctica casual a una metodología rigurosa y reproducible?

### Audiencia objetivo

- Profesores universitarios de ingenierías que quieren integrar IA responsablemente
- Estudiantes avanzados que ya usan IA pero sin método
- Administradores académicos preocupados por integridad y plagio

---

## El Pipeline de 8 Etapas

### Fase 1: Recolección (etapas 1-3)

**Etapa 1: Perplexity**
- Propósito: Exploración inicial, preguntas amplias, resúmenes de temas
- Herramienta: Perplexity AI
- Output: Ideas preliminares, términos de búsqueda, panorama general

**Etapa 2: Google Scholar**
- Propósito: Validación de fuentes, verificación de peer review, conteo de citas
- Herramienta: Google Scholar
- Output: Lista de referencias potencialmente válidas

**Etapa 3: Zotero**
- Propósito: Organización de biblioteca temática, gestión de referencias
- Herramienta: Zotero
- Output: Colección organizada, archivo .bib exportable

### Fase 2: Documentation as Code (etapas 4-7)

Todo en esta fase vive en un repositorio Git. El versionado es transversal a las cuatro etapas.

**Etapa 4: Diseño de Prompt**
- Propósito: Crear prompts estructurados que definan al agente como especialista
- Herramienta: Le Chat (Mistral) u otro LLM
- Output: Prompt versionado con rol, contexto, restricciones y formato

**Etapa 5: Bitácora de Investigación**
- Propósito: Registro sistemático de decisiones, hallazgos y callejones sin salida
- Herramienta: Archivos Markdown en repositorio
- Output: Entradas datadas que permiten reconstruir el razonamiento

**Etapa 6: Especificaciones (SRS/CR)**
- Propósito: Tratar experimentos como sistemas con requerimientos y control de cambios
- Herramienta: Claude Code con enfoque SDD
- Output: Documentos SRS y CR que formalizan alcance y evolución

**Etapa 7: Integración**
- Propósito: Consolidar todos los artefactos en el repositorio
- Herramienta: Git
- Output: Repositorio como fuente única de verdad del proyecto

### Fase 3: Producción (etapa 8)

**Etapa 8: NotebookLM**
- Propósito: Generar productos derivados a partir de documentos consolidados
- Herramienta: NotebookLM (Google)
- Output: Presentaciones, podcasts, infografías, guías de estudio

---

## Hallazgos Principales

### Hallazgo 1: Las alucinaciones son inevitables

Las alucinaciones no son "errores" que se puedan eliminar con mejor entrenamiento. Son consecuencia estructural de cómo funcionan los LLM: predicen la siguiente palabra más probable, no verifican verdad. Estudios recientes (Xu et al., 2025) demuestran matemáticamente esta inevitabilidad.

**Implicación:** No confíes en ninguna afirmación factual de un LLM sin validación externa.

### Hallazgo 2: El problema es metodológico, no ético

Cuando un LLM "alucina", no está mintiendo ni engañando. El modelo no tiene intención. El problema surge cuando el usuario acepta la respuesta sin verificar. La responsabilidad metodológica recae en quien usa la herramienta.

**Implicación:** Necesitamos alfabetización metodológica, no solo técnica.

### Hallazgo 3: Git resuelve la trazabilidad

El mismo sistema de control de versiones que usan los desarrolladores de software permite rastrear la evolución de un proyecto de investigación: qué prompts se usaron, qué decisiones se tomaron, cómo cambiaron los criterios.

**Implicación:** Documentation as Code no es solo para programadores.

### Hallazgo 4: El proceso es evaluable

En lugar de evaluar solo el producto final (el documento, la presentación), podemos evaluar el proceso que lo generó. Un repositorio con bitácora, SRS y control de cambios es evidencia de trabajo intelectual, distinguible del copy-paste de respuestas de IA.

**Implicación:** Los profesores tienen herramientas para evaluar uso responsable de IA.

---

## Aplicación en el Aula

### El problema actual

El 86% de estudiantes universitarios usan herramientas de IA generativa (Digital Promise, 2025). La mayoría lo hace sin estructura: copian prompts de internet, aceptan la primera respuesta, no verifican fuentes.

### Respuestas que no funcionan

1. **Prohibir IA:** Imposible de hacer cumplir, prepara mal a los estudiantes para el mundo laboral
2. **Permitir sin criterio:** Normaliza uso acrítico, degrada el aprendizaje

### La propuesta

Hacer del proceso el objeto de evaluación. El alumno no solo entrega el documento final; entrega el repositorio que muestra cómo llegó a él.

### Criterios de evaluación sugeridos

1. **Trazabilidad:** ¿Se puede reconstruir el proceso desde la idea inicial hasta el producto final?
2. **Validación:** ¿Las fuentes están verificadas? ¿Se distingue entre información confiable y especulativa?
3. **Iteración:** ¿Hay evidencia de refinamiento? ¿El alumno corrigió errores, ajustó enfoque?
4. **Reflexión:** ¿La bitácora muestra pensamiento crítico sobre lo que funcionó y lo que no?

---

## Frases Clave (para citas y highlights)

> "Los LLM no piensan. Predicen la siguiente palabra más probable. La diferencia no es semántica; es el fundamento de todo lo que sigue."

> "Las alucinaciones no son mentiras porque no hay intención de engañar. Son predicciones estadísticas que resultan ser falsas."

> "La IA no va a destruir la educación. El uso sin criterio de la IA sí puede hacerlo."

> "Evalúo cómo llegas al resultado, no solo el resultado. El repositorio es el examen."

> "De fichas bibliográficas a Google a IA: cada transición requirió nueva alfabetización. Estamos en otra."

> "El repositorio puede empezar hoy, con un archivo markdown y un primer commit."

---

## Preguntas Frecuentes (FAQs)

**¿Necesito saber programar para usar este pipeline?**
No. Git tiene interfaces gráficas (GitHub Desktop, VS Code). Markdown es texto plano con formato simple. Las herramientas están diseñadas para usuarios no técnicos.

**¿Cuánto tiempo adicional requiere?**
El tiempo de "overhead" inicial se recupera en la capacidad de retomar el trabajo semanas después sin perder contexto. La inversión es en trazabilidad, no en burocracia.

**¿Funciona para cualquier disciplina?**
El pipeline está diseñado para trabajo que involucre investigación, análisis o producción de documentos. Aplica a ingenierías, ciencias sociales, humanidades con componente de investigación.

**¿Qué pasa si mis alumnos no conocen Git?**
Enseñar Git básico toma una sesión. Es una competencia transferible que usarán en cualquier trabajo técnico. El costo de enseñarlo es menor que el beneficio de tenerlo.

**¿Esto no es demasiado para un proyecto de un semestre?**
Se puede escalar. Un proyecto simple puede tener solo bitácora y referencias. Proyectos más complejos usan el pipeline completo. La estructura es modular.

---

## Referencias Clave

1. **Xu et al. (2025)** - Demostración matemática de que las alucinaciones son estructuralmente inevitables en LLMs
2. **Farquhar et al. (2024)** - Método de entropía semántica para detectar confabulaciones (publicado en Nature)
3. **Digital Promise (2025)** - Estadísticas de uso de IA en educación superior (86% de estudiantes)
4. **Schulhoff et al. (2025)** - Taxonomía de 58 técnicas de prompt engineering
5. **Zieman (2023)** - Cinco pilares de reproducibilidad computacional

---

## Sugerencias para NotebookLM

### Para Audio Overview (podcast)
- Tono: Conversacional pero informado, como dos colegas discutiendo
- Enfoque: El problema (uso casual) → la solución (pipeline) → la aplicación (aula)
- Duración sugerida: 8-12 minutos

### Para presentación de slides
- 10-12 slides máximo
- Una idea por slide
- Incluir el diagrama del pipeline de 8 etapas
- Cerrar con los 4 criterios de evaluación

### Para guía de estudio
- Organizar por las 8 etapas
- Incluir preguntas de comprensión para cada etapa
- Agregar ejercicio práctico: "Crea tu primer repositorio de investigación"

---

## Licencia

Este documento está licenciado bajo Creative Commons Atribución 4.0 Internacional (CC BY 4.0).
